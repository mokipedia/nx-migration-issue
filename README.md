# Migration issue with binaries - showcase repo

This repo is for showcase purposes of NX Issue 4024
https://github.com/nrwl/nx/issues/4024

# Steps taken

1. `ng new nx-migration`
2. add fonts to src folder, e.g. in scss folder
3. `ng add @nrwl/workspace` for migration to nx workspace
4. fonts are broken now (binary files modified)
