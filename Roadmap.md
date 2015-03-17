### Current Work ###

**Version 5.3 (Mid 2010)**
  * ~~Minor code fixes (not security related)~~
  * ~~Fix C++ Builder compatibility (deactivate abstract methods automatically with BCB)~~
  * ~~Adjust Compile-Time options (ASM, PRNG, Inlining, RTTI)~~
  * ~~Enhance Unicode Examples~~
  * ~~Check used Pointer Math~~
  * ~~Introduce Exception descendants allowing distinct error handling~~
  * Rewrite of the Format Encoding/Decoding (10% done)
  * Rewrite of the String/Data Handling (30% done)
  * Source Review and Code Formatting (80% done)
  * Create a GUI-based Demo (40% done)
  * Implement simple Self Tests (Format/Hash/Cipher), invoke automatically and/or manually
  * Introduce Unittests (replacing DECTest.dpr) using above mentioned Self Tests

~~strikeout~~ = done

### Under Consideration ###

**Version 5.3**
  * Implement CTR Block Mode

**Version 5.4**
  * Implement additional Ciphers
  * Implement additional Hash Functions
  * Implement additional PRNGs
  * Extend CRC functionality (predefined rocksoft parameter combinations, CRC64)
  * FreePascal Port (only i386+)