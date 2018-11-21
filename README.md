(OSS-QM project) flatbuffers
============================

* Upstream: https://github.com/google/flatbuffers

* Generic maintenance branches:
    * [maint-1.9.0](https://github.com/oss-qm/flatbuffers/tree/maint-1.9.0)
        * CMakeLists: fix installation of flatc and flathash binaries
            https://github.com/google/flatbuffers/pull/5050
        * fix missing pkg-config descriptor (.pc file)
            https://github.com/google/flatbuffers/pull/5062
* Packaging branches:
    * [debian/maint-1.9.0](https://github.com/oss-qm/flatbuffers/tree/debian/maint-1.9.0): generic debianization (should also work on derivatives)

* More work to do:
    * build/install shared library, in order to allow quick fixes without
      recompiling depending applications and save some memory
    * probably needs MVCC installation
