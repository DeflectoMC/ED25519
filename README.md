A faster Ed25519 Java implementation that can run on Android

This is the original Ed25519 implementation sped up a bit.
I unrolled some code, used built in functions to replace java
methods, and converted a recursive call into a loop.

I tested it alongside the original implementation to make sure
the functionality didn't change.

Mick Michalski
