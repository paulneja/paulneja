<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/profile-header-dark.svg" />
  <img src="assets/profile-header.svg" width="100%" alt="paulneja - low-level systems, security and full-stack development" />
</picture>

<p align="center">
  <a href="mailto:paulnejacontacto@gmail.com">Email</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/paulneja?tab=repositories">Repositories</a>
  &nbsp;&middot;&nbsp;
  <a href="#notes-from-the-projects">Technical notes</a>
</p>

Most of my public work is around Linux: kernel changes, boot chains and software
for small machines. I also build full-stack applications and run DevPocket.

## Selected work

<a href="https://github.com/paulneja/Linux-on-esp32-S3">
<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/esp32-mobile-dark.svg" />
  <source media="(max-width: 600px)" srcset="assets/esp32-mobile.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/esp32-dark.svg" />
  <img src="assets/esp32.svg" width="100%" alt="Linux 7.2.4 on ESP32-S3: 16 MB flash, 8 MB PSRAM, Wi-Fi, SSH, Bash and MicroPython. Worst switch between three busy Bash processes: 29.3 ms copying vs. 5.2-5.6 ms with cache-MMU remapping on the same 0.9 image. 36/36 board tests, 10/10 extra checks, 20/20 clean cold boots." />
</picture>
</a>

<p align="center">
  <a href="https://github.com/paulneja/Linux-on-esp32-S3#quick-start"><b>Flash it</b></a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/paulneja/Linux-on-esp32-S3/blob/main/build/verification/2026-10-04-release.md">Measurements</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/paulneja/linux-esp32s3">Kernel source</a>
  <br />
  <sub>Cache-MMU remapping speeds up bank switching. Still no per-process protection or copy-on-write.</sub>
</p>

<p align="center">
  <a href="https://github.com/paulneja/Linux-on-esp32-S3#quick-start">
    <img src="https://raw.githubusercontent.com/paulneja/Linux-on-esp32-S3/main/docs/demo.svg" width="720" alt="Recording from the real board: Linux boots, followed by login, uname, free, a Bash fork, MicroPython and ping." />
  </a>
  <br />
  <sub>From the board's serial console. Long pauses shortened to 1.6 seconds.</sub>
</p>

<p align="center">
<a href="https://github.com/paulneja/Zevory-Linux"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/zevory-dark.svg" />
  <img src="assets/zevory.svg" width="390" alt="Zevory Linux: Limine to Linux to ZevInit, a Rust PID 1. Shell lifecycle, orphan reaping and shutdown. The bootstrap has run on hardware; ZevInit has only been tested in QEMU." />
</picture></a>
<a href="https://github.com/paulneja/Syscage"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/syscage-dark.svg" />
  <img src="assets/syscage.svg" width="390" alt="SysCage: ELF and Windows PE analysis using Bash, namespaces, a temporary rootfs, strace and Wine. Collects traces, traffic and dropped files. Shared-kernel isolation, not a VM; use disposable analysis environments." />
</picture></a>
</p>

## Notes from the projects

<p align="center">
  <a href="https://github.com/paulneja/Linux-on-esp32-S3/blob/main/ARCHITECTURE.md">Inside the S3 port</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/paulneja/Linux-on-esp32-S3/blob/main/build/verification/2026-10-04-release.md">Release verification</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/paulneja/Zevory-Linux/blob/main/zevinit/README.md">Inside ZevInit</a>
</p>

---

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/paulneja/paulneja/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/paulneja/paulneja/output/github-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/paulneja/paulneja/output/github-snake-dark.svg" />
</picture>
</div>
