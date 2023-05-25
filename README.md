# nix-installer-action-benchmark

I was curious which installer was faster.

## Currently benchmarked installers
* [nixbuild/nix-quick-install-action@master](https://github.com/nixbuild/nix-quick-install-action)
* [cachix/install-nix-action@master](https://github.com/cachix/install-nix-action)
* [DeterminateSystems/nix-installer-action@main](https://github.com/DeterminateSystems/nix-installer-action)

## Results

Based on 1 GitHub actions run.

| installer           | os            | time |
|---------------------|---------------|-----:|
| nixbuild            | ubuntu-latest |    2s|
| nixbuild            | macos-latest  |   14s|
| cachix              | ubuntu-latest |    5s|
| cachix              | macos-latest  |   42s|
| determinate-systems | ubuntu-latest |   17s|
| determinate-systems | macos-latest  |   49s|

