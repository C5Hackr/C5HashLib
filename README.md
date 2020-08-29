# C5HashLib
A Hashing Lib for C#.

--------------------

Usage: 

--- Auto Updater: AutoUpdater.InitAutoUpdater(); <-- Run this at start/beginning of program to avoid "Incorrect Version" error message!

--- HashLib: C5HashLib.HashMethodHere();

--- HashLib Methods: VMHash(string Input), SerializeHash(string Input), ParseHash(string Input), LexHash(string Input), CipHash(string Input), C4T(string Input).

--- Best/Most Secure Methods: 1, VMHash, 2, ParseHash.

--- Medium/Semi-Secure Methods: LexHash.

--- Least Secure Methods: CipHash, C4T.


Note: VMHash is a VM (Virtual Machine) and what it does is it takes your input and virtualizes the strings to make them short and SUPER SECURE and uncrackable (Most Secure Method).

Note: To read the hash first hash a string then check the hash to see if it matches, EXAMPLE - string hash = C5HashLib.VMHash("a") => 0x786ANDD | string checkhash = C5HashLib.VMHash("a") => 0x786ANDD => hash matches so continue.

Note: It is NOT recommended to use special characters such as !@#$%^&*()_+-}{[]|\';:",./?>< and etc, etc, etc.

Note: t is NOT recommended to hash things 2 or more times with DIFFERENT hasher's/encryptor's if you want to hash/encrypt somthing more then once and have it still be able to be read then only hash/encrpyt multiple times with 1/the same hasher/encrpytor!
