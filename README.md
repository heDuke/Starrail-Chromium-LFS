# Starrail Chromium large source fixtures

Public Git LFS storage for the pinned source module at
https://github.com/heDuke/Starrail-Chromium . GitHub prohibits adding new LFS
objects to the upstream Chromium public fork network, so the module's tracked
`.lfsconfig` uses this independent public repository as its LFS endpoint.

`objects/vk-master-NOT_SUPPORTED.txt` is the complete, unchanged local file
`third_party/swiftshader/tests/regres/testlists/vk-master-NOT_SUPPORTED.txt`.
The original SwiftShader `LICENSE.txt` and authors/contributors files accompany
it. Its source commit is recorded by the module's `starrail/source-manifest.json`.
No private Starrail application source is included here.

Use Git LFS to retrieve the original file. The main source module resolves this
object automatically after `git lfs pull`; GitHub's automatic source ZIP does
not include files hosted through a custom LFS endpoint.
