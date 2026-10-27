# Organization profile visuals

`banner.svg` shares the desktop and mobile README palette and layout.

The organization profile uses copies of the apps' original offline preview screenshots. Update the source repository's images and these copies together when the interface changes:

- `desktop-session.png`: desktop commit `2832322120179c77c62db512ef89aaf912af4160`, `--visual-preview`, output `combined-large.png`.
- `ios-library.png`: mobile Actions run [40511677969](https://github.com/Achievement-Labs/achievement-labs-mobile/actions/runs/40511677969), iOS Simulator Checks artifact, `iPhone-library.png`.
- `android-session.png`: mobile Actions run [40511229450](https://github.com/Achievement-Labs/achievement-labs-mobile/actions/runs/40511229450), Android Screens artifact, `Android-queue.png`.

These are actual app interfaces with synthetic sample data. Keep the preview caption and check replacement images for private account information. The profile's absolute image URLs target this repository's `main` branch so they work on the organization overview after merging.
