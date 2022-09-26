# NEARBY
The nix registry replacement middleware

## What is it?

Just as the name suggests it connects nix or/and an binary cache and proxies it so different package managers can use it as registry.
However without ever having a real registry or the withdrawals of a real registry. No state is stored ever.

To publish packages you just create a nix expression which points to a commit of a git repository that is nix-buildable. Whenever the "registry" middleware receives a request to a specific package and version it will either deliver a preivous build one from the nix-binary cache or build it on demand for the package manager.

That way it is possible to omit the traditional registry where evil state is stored.
Instead you can use a "private registry" and use tools like npm, maven, apt etc. for developing awesome stable and reproducible apps. 

Prevent unwanted mess in a real registry, be not storing any state and finally use a registry what it should be: only a cache. 

## Status

- 🟩 Draft the idea

- 🟦 Implement a first Prototype

## Contribute

Feel free to send me your PR 

Feature requests / issues also welcome !
