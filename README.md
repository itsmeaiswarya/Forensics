# Forensics

1. The Office Trouble 1 
  * Initially downloaded the zip file given and also downloaded rockyou.txt from [Link](https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt)
  * Then used the command1: sudo apt-get install fcrackzip
  * Then used the command2: fcrackzip -b -D -p rockyou.txt -u av_b62152ea-cc85-43ab-8af1-f39915814327.zip
  * Finally cracked the zip file with the password 'perfectlypunk' and thus retrived the flag: inctfj{dw1ght_1s_cr4zy_bu7_awes0me}
