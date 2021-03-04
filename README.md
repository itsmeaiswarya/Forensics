# Forensics

1. The Office Trouble 1 
  * Initially downloaded the zip file given and also downloaded rockyou.txt from [Link](https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt)
  * Then used the command1: sudo apt-get install fcrackzip
  * Then used the command2: fcrackzip -b -D -p rockyou.txt -u av_b62152ea-cc85-43ab-8af1-f39915814327.zip
  * Finally cracked the zip file with the password 'perfectlypunk' and thus retrived the flag: inctfj{dw1ght_1s_cr4zy_bu7_awes0me}

2. Snow Snow
  * Initially installed stegsow using: $ sudo apt install stegsnow
  * Then gave the command: stegsnow -C  av_a0b05a70-7bc0-419e-bc50-147852117b9c.txt
  * Got the flag: ntio{eP1B35x4K3_aB3O0_q5_K00t} 
  * Converted the flag using ROT8: flag{wH1T35p4C3_sT3G0_i5_C00l}
  * [Link](https://wiki.bi0s.in/steganography/stegsnow/#decryption) for reference

3. Security 101
  * FLag - ntio{eP1B35x4K3_aB3O0_q5_K00t}

  
