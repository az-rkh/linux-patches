# Linux Kernel Patches

Patches submitted to the Linux kernel mailing list by [Azamat Rakhim](mailto:azamatrakhim8@gmail.com).

## Patches

### Subsystem: `staging/rtl8723bs`

| # | Patch | Status | Lore Link |
|---|-------|--------|-----------|
| 1 | staging: rtl8723bs: use u8 instead of int for bssrate_len in get_rate_set() | Reviewed | [lore](https://lore.kernel.org/20260210165437.24550-1-azamatrakhim8@gmail.com/) |
| 2 | staging: rtl8723bs: use u8 instead of unsigned char in get_rate_set() | Reviewed | [lore](https://lore.kernel.org/20260209180303.53957-1-azamatrakhim8@gmail.com/) |
| 3 | staging: rtl8723bs: simplify boolean test in rtw_btcoex_MediaStatusNotify (v2 1/2) | Reviewed | [lore](https://lore.kernel.org/20260208175120.15717-1-azamatrakhim8@gmail.com/) |
| 4 | staging: rtl8723bs: remove extra blank lines in rtw_btcoex.c (v2 2/2) | Reviewed | [lore](https://lore.kernel.org/20260208175120.15717-2-azamatrakhim8@gmail.com/) |
| 5 | staging: rtl8723bs: clean up checkpatch warnings in rtw_btcoex.c | Reviewed | [lore](https://lore.kernel.org/20260207210124.10094-1-azamatrakhim8@gmail.com/) |
| 6 | staging: rtl8723bs: remove unused MAX_PATH_NUM defines for other chips | Reviewed | [lore](https://lore.kernel.org/20260215155659.67324-1-azamatrakhim8@gmail.com/) |
| 7 | staging: rtl8723bs: remove unused rtl8192c_query_rx_desc_status declaration (v1 1/2) | Superseded | [lore](https://lore.kernel.org/20260313190658.13525-1-azamatrakhim8@gmail.com/) |
| 8 | staging: rtl8723bs: remove unused rtl8192c_translate_rx_signal_stuff declaration (v1 2/2) | Superseded | [lore](https://lore.kernel.org/20260313190658.13525-2-azamatrakhim8@gmail.com/) |
| 9 | staging: rtl8723bs: replace rtl8192c_recv.h with rtl8723b_recv.h (v2) | Reviewed | [lore](https://lore.kernel.org/20260314190704.11945-1-azamatrakhim8@gmail.com/) |

## About

These patches address items from the `rtl8723bs` driver's TODO list in the `staging` subsystem, including type cleanups and code style fixes.

Patch files are available in the [`patches/`](patches/) directory.
