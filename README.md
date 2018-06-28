# osgEphemeris

An ephemeral model including a star database, sun, moon and planets of the
solar system. When using osgEphemeris, the user provides the software with
latitude, longitude, date, and time, and the software will provide a ground
(or near-ground) view of the sky with the sun, moon, planets, and stars all
positioned with reasonable accuracy.

## Building and Installing
```bash
mkdir build
cd build
cmake ..
make -j8
sudo make install

```