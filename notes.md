## Magisk (fd5ad91d) (20423)
- Fix bootloop on legacy rootfs based devices
- Fix incorrect 2SI detection that always report incorrect results (that will also fix tons of bootloops)
- Update SELinux rules, fixing several issues

## Magisk Manager (fbaf2bde) (297)
- Fix several bugs in manager upgrade logic.
It should now successfully upgrade under all circumstances after this build.
If you ran into "cannot parse package" error, clear the app cache and try again.
- Allow arbitrary package name and app label length for repackaging
