# NEARBY
Nix Verdaccio Plugin

NEARBY stands for: Nix vERdacio BinarY cache 

## What is it?

Just as the name suggests it connects nix or an binary cache and proxies it so npm / node can use it as registry.
However without the withdrawals of an real registry. No state is stored in the verdaccio private registry.
 In fact it is impossible to publish packages to it (with this plugin) you can instead publish a nix expression that points to an buildable artifact from a nixified node package.

That way it is possible to omit the traditional registry where evil state is stored.
Instead you can use a "private registry" and use npm/yarn and also nix for developing awesome apps. 

Using the awesome reproducavility from nix to prevent unwanted mess in a real registry. 

## Contribute

Feel free to send me your PR 

Feature requests / issues also welcome !
