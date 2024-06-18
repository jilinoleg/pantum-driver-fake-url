Hack to download pantum drivers on NixOS after package got broken by the change on manufacturer's side

# The problem

Pantum printers manufacturer's site started to seemingly restrict automated downloads of their driver. As Nix fetchers cannot set user agents, it cannot download the package and cannot build it.

# The solution

I reuploaded package to Github releases without any changes. I'll see if it works.

Update 1: It seems to build without errors

# License

This repository is not related to Pantum in any way nor implies endorsement on their part. This repository is made for sole purpose of temporarily fixing workflow that relies on automated downloads. 
