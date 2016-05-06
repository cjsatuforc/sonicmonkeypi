# sonicmonkeypi
A Raspberry Pi (and small Linux) incarnation of my Android app of the same name. A dynamic ambient drone noise machine that draws from the latest FreeSound Community content, based on configurable keywords.
Watch an early sample run: https://www.youtube.com/watch?v=hHADwchSK6U

# Required
1. *nix with /bin/sh
2. Perl (3+?) - sudo apt-get install perl
3. curl       - sudo apt-get install curl 
4. sox        - sudo apt-get install sox
5. FreeSound.org API key, from freesound.org/help/developers/

# Setup
1. Put the kit's files in a directory
2. Paste your API key into token.txt
3. Optional: Edit keywords.txt / format.txt

# Run: Using built-in + keywords.txt:
      perl sonicmonkeypi

# Run: Add keyword 'monkeys' this time only:
      perl sonicmonkeypi monkeys

# Run: Use only keyword 'monkeys':
      perl sonicmonkeypi =monkeys

# Bugs:
Soo many. Almost no error checking. No cache expirey yet either!
