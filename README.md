# bins

Short, crafty and questionably useful.

## Installation

Use `lnbins` to create symbolic links to this local git repository from any
given bin directory. The following will install all Linux related links:

```
git clone https://github.com/dustinrc/bins
cd bins
./lnbins _linux $(pwd) $HOME/bin
```

Similarly, use `_osx` and `_vm` for OS X and [DigitalOcean] VMs, respectively.

[DigitalOcean]: https://www.digitalocean.com/?refcode=114813747e5f
