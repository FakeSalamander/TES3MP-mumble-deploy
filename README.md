# TES3MP-mumble-deploy

Script that simplifies the installation, upgrade and packaging of TES3MP-mumble


## Usage

```
./tes3mp-deploy.sh --help
```

Can be used in conjunction with [TES3MP-forge](https://github.com/GrimKriegor/TES3MP-forge) to quickly create distributable packages that support a wide range of GNU/Linux distros and architectures.

```
./tes3mp-deploy.sh -C armhf --install --make-package --version "0.8.1" --server-only
```


## Attribution

Thank you to GrimKriegor for the original TES3MP-deploy script.

Big thanks to Testman, Shnatsel, Shatur and the TES3MP community for their intense testing, debugging contributions and suggestions.

Additional gratitude to FreeAethernet and Joe for their relentless testing of the auto generated packages.
