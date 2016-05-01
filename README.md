###Build Status :syringe:




<hr>
<b>01/05/16</b> :alarm_clock:
* Completed overhaul of the build `librtmp`
* Reframing build OpenSSL - - - :construction: <b>Now Here :arrow_left:</b>

<hr>
<b>29/04/16</b> :alarm_clock:
* Working on `librtmp`, for upgrade to version of `OpenSSL 1.0.2g` (**1%** - Scheduled Task Start 14h~15h, -3 GMT)
* Fixed librtmp build with `OpenSSL 1.0.2g` - Compiling with success (x86)
* Finished `librtmp`  test build (**100%** - `librtmp 2.4` and `OpenSSL 1.0.2g` :ok:)
* Working on all build system, to automatically detect the CPU ABI and apply the version of the libraries, creation and standardization of directories and destination files. Many changes (_In progress_)

<hr>
<b>28/04/16</b> :alarm_clock:
* Success to make config for `x86` others will work fine.

<hr>
<b>27/04/16</b> :alarm_clock:
* Making several changes
* Slow fixing `FFmpeg 3.0` for Vitamio Android :camel:
* Build have errors, but we are fixing it slowly :camel:
* Fixed `FFmpeg 3.0.1` Build to Vitamio :ok:
* Trying to fix `OpenSSL 1.0.2g` for Vitamio :fire:
* Fixed `OpenSSL 1.0.2g` `build.sh` for `arm` (StandAlone files, they need to be copied and organized in their respective directories, according to the standards of vitamio and `librtmp`) :ok:
* Trying to make config for `mips`, `x86` and others CPU ABI's

<hr>
<b>17 to 20/04/16</b> :alarm_clock:
* Project is slow development
* All Compile Failed, tryn new configs
* `librtmp` working as good, now we nedd to make `openssl` work.
* Machine has ERROR
* Building a new VMware machine `Centos 7 x64`
* `OpenSSL 1.0.2g` dont generate obj folder into CPUABI `obj/local/armeabi/`<obj needed, dont generate>
* `FFmpeg` Compiling problem(Android NDK), tryng to solve, to compile
* Fixed `NDK` problem on compile `FFmpeg`

<hr>
<b>16/04/16</b> :alarm_clock:
* Machine updated with `Build-Essentials`
* NEW Pre-BUILD Found
* Trying to complile Pre-BUILD complete of `FFmpeg` + `OpenSSL` + `librtmp` (OUTDATED VERSIONS)
* :white_check_mark: <u>`Build SUCCESS`</u>
* Making Build BACKUP
* Trying to make some changes to upgrade build to last version of `FFmpeg`

<hr>
<b>15/04/16</b> :alarm_clock:
* Tryinto to compile
* :bangbang: Build FAILED
* :x: <s>Build DELETED</s>

<hr>
<b>15/04/16</b> :alarm_clock:
* NEW BUILD Clean of `FFMPEG` + `openssl`
* Trying to compile
* Compilation sucess `FFMPEG(N-79430-g89ec4d4)` and `OpenSSL(Version 1.0.1e)`
* Trying to compile with `librtmp`
* :bangbang: Build FAILED - `FFMPEG(N-79430-g89ec4d4)`, `OpenSSL(Version 1.0.1e)` and OFFICIAL VITAMIO `librtmp`
* Trying with others config
* :bangbang: Build FAILED
* Trying with other versions of `librtmp`
* :bangbang: Build FAILED

<hr>
<b>14/04/16</b> :alarm_clock:
* Clean Machine created to build Vitamio compilations
* Trying to compile OFFICIAL VITAMIO build (FFmpeg-Vitamio/librtmp/OpenSSL-Vitamio)
* Compilation totally failed in multiple configurations
* :x: <s>Build DELETED</s>
