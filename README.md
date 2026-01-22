# ZenDeobfuscator
Simple deobfuscator for .NET assemblies protected with Zenfuscator / Project Zen.

Target framework: .NET Framework 4.7.2
Library: dnlib

Features

Removes ObfuscatedByProjectZen module name watermark

Removes fake attributes and junk types

Removes anti-de4dot FormXXX attribute types

Decrypts Base64 string protection

Saves output as .unpacked.exe / .unpacked.dll

Limitations

Original names cannot be restored

Supports only Zenfuscator-style protection

Not a universal deobfuscator

Usage
ZenDeobfuscator.exe target.exe

Output:

target.unpacked.exe

