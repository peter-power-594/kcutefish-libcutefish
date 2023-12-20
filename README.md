# System Library

## OpenMandriva Dependencies

```shell
sudo dnf in task-develop
sudo dnf install lib64KF5BluezQt-devel lib64KF5Screen-devel lib64qt5test-devel lib64qt5sensors-devel lib64canberra-devel 
```


## Build

```shell
mkdir build
cd build
ccmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Install

```shell
sudo make install
```

## License

This project has been licensed by GPLv3.
