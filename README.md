
<p align="center">
  <img src="bens-home-icon-512.png" alt="Bens Home Repo logo" style="width:256px;height:256px;"/>
</p>

<div align="center">

[![Twitter](https://img.shields.io/badge/Twitter-white?style=for-the-badge&logo=Twitter&logoColor=black)](https://twitter.com/BenjaFriend)
[![My Work](https://img.shields.io/badge/My_Work-white?style=for-the-badge&logo=jekyll&logoColor=black)](https://benhoffman.tech/)
[![Github](https://img.shields.io/badge/Github-white?style=for-the-badge&logo=jekyll&logoColor=black)](https://github.com/BenjaFriend?tab=repositories)

</div>

# Base

This is the base repo for my home server stack. This is designed so that it can be cloned onto a fresh server install and give me everything that I want. It's built up of various submodules so that I can do different versioning and branching for each feature if desired.

This is really just for my own personal use and organization. 

## Geting Started

Clone this repo with SSH:

```
git clone git@github.com:bens-home/base.git
```

Initalize all the submodules in the repo

```
git pull --recurse-submodules
```

or

```
git submodule update --init --recursive
```

The submodules are added with the SSH path, so you need to have that set up on your git account.