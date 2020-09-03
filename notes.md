## Magisk (f32a2991) (20421)
- Properly detect 2SI init, should fix Android 11 support on many devices

## Magisk Manager (fbaf2bde) (297)
- Fix several bugs in manager upgrade logic.
It should now successfully upgrade under all circumstances after this build.
If you ran into "cannot parse package" error, clear the app cache and try again.
- Allow arbitrary package name and app label length for repackaging
