# nix-installer-action-benchmark

I was curious which installer was faster.

## Currently benchmarked installers
* [cachix/install-nix-action@master](https://github.com/cachix/install-nix-action)
* [DeterminateSystems/nix-installer-action@main](https://github.com/DeterminateSystems/nix-installer-action)

## Results

Based on 1 GitHub actions run.

| installer           | os            | time |
|---------------------|---------------|-----:|
| cachix              | ubuntu-latest |    4s|
| cachix              | macos-latest  |   44s|
| determinate-systems | ubuntu-latest |   18s|
| determinate-systems | macos-latest  | 1m41s|
