# CVE-2019-11477-ubuntu-livepatch


github kpatch 0.4


kpatch-build -t vmlinux ubuntu-4.4.0-62-generic.patch  --skip-gcc-check


kpatch load kpatch-ubuntu-4-4-0-62-generic-CVE-2019-11477.ko
