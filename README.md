# VLID-morse-flash-password
Program to encode 

This program is to be run on an Arduino UNO microprocessor board as a part of a visible light identification (VLID) door locking system. The unlock sequence of the system would be activated upon reception of an LED flash sequence password output from a phone via the system's companion application, denoted FlashKey. The aim was to create a VLID lock that was as efficient, secure and reliable as a traditional key lock, or as other types of commercially available electronic locks (e.g. RFID or biometric).

The aim of this program was to encode a vey specific password sequence and for the photoreception to be highly discerning to maintain security. In the end this was acheived through standardising the flash sequence into a string of unit length pulses, that were then translated into a morse code sequence. This made the code more intuitive to the reader and to myself as I wrote it. The unit length can be adjusted to adjust security/efficiency, and the password itself can be set as a word in morse code.

The aim was met; the code is highly efficient when run on the Arduino as part of the light detecting/locking system. The password detection proved to be extremely relaible when tested under controlled conditions. An incoming flash sequence with deviation of any kind from the expected password will fail to activate the unlock sequence.
