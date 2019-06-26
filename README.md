# Changes Explained
We made the following changes to the original repo to make it build (`ubuntu 19.04`, `x86_64`).
- `test/CMakeLists.txt`: correct file name from `data/Parameters.cpp` to `data/parameters.cpp`
- `CMakeLists.txt` (you probably don't need to do 1 and 2 if you are not building tests):
  1. Install libgtest-dev and link it
  2. Link pthread
  3. Link X11
  4. Link `libdl` with `${CMAKE_DL_LIBS}`

---

# libmediasoupclient

C++ client side library for building [mediasoup][mediasoup-website] based applications built on top of [libwebrtc][libwebrtc].



## Website and Documentation

* [mediasoup.org][mediasoup-website]


## Support Forum

* [mediasoup.discourse.group][mediasoup-discourse]


## Authors

* José Luis Millán [[website](https://jssip.net)|[github](https://github.com/jmillan/)]
* Iñaki Baz Castillo [[website](https://inakibaz.me)|[github](https://github.com/ibc/)]



## License

[ISC](./LICENSE)




[mediasoup-website]: https://mediasoup.org
[mediasoup-discourse]: https://mediasoup.discourse.group
[libwebrtc]: https://webrtc.org/native-code
