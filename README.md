# How to build and install

KFParticle depends on [ROOT](https://root.cern) so, make sure it is installed and
`root-config` is in your `PATH`

```shell
git clone https://github.com/psilib/KFParticle.git
cmake -S KFParticle -B build -DCMAKE_INSTALL_PREFIX=install
cmake --build build
cmake --install build
```
