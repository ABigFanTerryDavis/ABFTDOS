ABFTDOS (A Big Fan Terry Davis OS)
Plan / Planning Phase

SCOPE:
- Android-based full custom ROM (AOSP/Lineage base)
- Custom apps and branding added
- Build via GitHub Actions (planned)
- Test on Android Studio Emulator (planned)
- Linux build: planned, no code written yet

CURRENT STATUS:
- Planning phase only
- Linux build NOT started (no code yet)
- AOSP source not downloaded (50GB+)
- GitHub Actions workflow not configured yet

REALITY CHECK:
- AOSP builds need 32GB+ RAM, 200GB+ disk, hours to compile
- GitHub Actions free runners: 2 cores, 7GB RAM, 6-hour timeout
- Emulator testing requires Android SDK + system images
- Next step: create manifest, branding assets, custom app skeleton

NEXT ACTIONS:
1. Initialize repo with manifest (lineageos/android)
2. Add custom branding (boot animation, logo, name)
3. Build skeleton custom app package
4. Configure .github/workflows/ for build/test (future)
5. Linux build: deferred until planning complete
