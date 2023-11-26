# io.github.mgoeppner.EVEMon
A lightweight, easy-to-use application designed to assist you in keeping track of your EVE Online character progression.

[https://github.com/mgoeppner/evemon](https://github.com/mgoeppner/evemon)

## How to install EVEMon as a flatpak locally

These commands will build and install EVEMon as a flatpak locally for your user:
```bash
git clone -b io.github.mgoeppner.EVEMon https://github.com/NullsecSpace/io.github.mgoeppner.EVEMon.git
cd io.github.mgoeppner.EVEMon
flatpak-builder --install --user --force-clean build-dir io.github.mgoeppner.EVEMon.yml
```

## How to update EVEMon locally
To update your locally built flatpak version of EVEMon run the following commands:
```bash
cd io.github.mgoeppner.EVEMon
git pull
flatpak-builder --install --user --force-clean build-dir io.github.mgoeppner.EVEMon.yml
```

## How to run EVEMon
```bash
flatpak run io.github.mgoeppner.EVEMon
```

## How to uninstall EVEMon
```bash
flatpak uninstall --user io.github.mgoeppner.EVEMon
```


