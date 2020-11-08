## violet-x86_64 <img alt="Visits" align="right" src="https://badges.pufler.dev/visits/owl4ce/violet-x86_64?style=flat-square&label=&color=success&logo=GitHub&logoColor=white&labelColor=373e4d"/>

- Xanmod based patchset  
https://gitlab.com/src_prepare/src_prepare-overlay/-/tree/master/sys-kernel/xanmod-sources
- bzImage: LZ4
- Cachy CPU Scheduler  
https://github.com/hamadmarri/cachy-sched
- Disable numa & tracing
- AMD only
- Enable RAM compressed block as default: LZ4
- Governor performance

---
*/usr/src/linux*
```bash
make -j`nproc` menuconfig
make -j`nproc` modules_install
make -j`nproc` install
```
<p align="center">
  <img alt="neofetch" align="center" src="https://i.ibb.co/dGT7TXx/2020-11-08-113106-581x492-scrot-framed.png"/>
</p>
