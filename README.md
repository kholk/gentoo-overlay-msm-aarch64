# gentoo-overlay-msm-aarch64

Current work done on Sony devices, this allows to get
native support on Gentoo, with downstream kernels, for
various features on Qualcomm SoCs.
Currently experimented on a prefixed installation.

This includes, but is not limited to:
1. Native audio support through ALSA and Pulseaudio
2. Venus VENC/VDEC

TODOs:
- ACDB support for PulseAudio
- Camera
- Telephony
- Full OpenCL support on Adreno 4xx, 5xx, 6xx.

Currently not planned (contributions are anyway welcome):
- X11 (this is a big NO!)
- Wayland support (possible and relatively easy to get)
