## Magisk (11f254e5) (20424)
- Fix SELinux rules from Android 8.0 to 10

## Magisk Manager (fbaf2bde) (297)
- Fix several bugs in manager upgrade logic.
It should now successfully upgrade under all circumstances after this build.
If you ran into "cannot parse package" error, clear the app cache and try again.
- Allow arbitrary package name and app label length for repackaging
