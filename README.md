# sonicmonkeypi
PI (and other small Linux) incarnation of my Android app "Sonic Monkey", the ambient drone noise machine.

# Required
1. *nix with /bin/sh
2. Perl (3+?) - sudo apt-get install perl
3. curl       - sudo apt-get install curl 
4. sox        - sudo apt-get install sox
5. FreeSound.org API key, from freesound.org/help/developers/

# Setup
1. Place API key in token.txt
2. Optional: Edit keywords.txt
3. Optional: Edit format.txt

# Run: Using built-in + keywords.txt:
      perl sonicmonkeypi

# Run: Add keyword 'monkeys' this time only:
      perl sonicmonkeypi monkeys

# Run: Use only keyword 'monkeys':
     perl sonicmonkeypi =monkeys

# Bugs:
So many. Almost no error checking. No cache expirey yet either!
