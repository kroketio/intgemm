#  intgemm

Fork of [kpu/intgemm](https://github.com/kpu/intgemm) made for [kotki](https://github.com/kroketio/kotki).

### as system lib

```bash
cmake -DCMAKE_BUILD_TYPE=Release -DINTGEMM_DONT_BUILD_TESTS=ON -Bbuild .
make -Cbuild -j6
sudo make install
```

Also writes a CMake config and pkgconfig.
