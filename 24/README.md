

This repositry is based on Leo's bonus exercises for the LibreLane 
template for SG13G2 process

# Full chip design using 24 pins padframe


> [!WARNING]
> Full chip design with ihp-sg13g2 is currently in testing phase.

In order to create a full chip design we need to generate a pad ring. LibreLane have support for automatic pad ring generation in the development branch [librelane/dev](https://github.com/librelane/librelane/tree/dev) branch.

Invoke `nix-shell` in the directory `24/` of this repository. That will enable the correct LibreLane version.
One have to also switch to the `dev` branch of the PDK.

Running `make libralane` will execute the flow. 



