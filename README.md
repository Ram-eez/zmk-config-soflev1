# ZMK Config for Sofle v1 (Dongle)

The dongle connects to the computer; both halves connect to the dongle.

- Built for `nice_nano_v2` (nice!nano v2, also works on SuperMini nRF52840 Pro Micro).
- Flash `settings_reset` on **all three** boards first (dongle, left, right).
- Then flash `sofle_dongle`, `sofle_left` and `sofle_right`.
- Pair only the dongle with your computer.
- To go back to a no-dongle setup: remove the `cmake-args` and the dongle from `build.yaml`, reset settings, and reflash.
