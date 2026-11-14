# iOS 16 unsigned IPA build

One-off CI build of the upstream HGhubX source plus the iOS 16 playback fix.

- `ios16-playback-fix.patch` is applied only inside the CI workspace by
  `.github/workflows/ios16-build.yml`; no source file in this repository is modified.
- Output: an unsigned `.ipa` uploaded as the `ios16-unsigned-ipa` Actions artifact.
- Edit this file (or the workflow) and push to `main` to retrigger the build.
