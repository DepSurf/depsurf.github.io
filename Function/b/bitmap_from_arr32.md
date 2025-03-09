# Function: <code>bitmap_from_arr32</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583839440,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1135",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583839440,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922144,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1149",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922144,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584102080,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1177",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584102080,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224864,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1197",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224864,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584630464,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1272",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630464,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584749520,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1272",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584749520,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777856,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1315",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777856,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207872,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1446",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207872,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043792,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1476",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043792,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587026624,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1457",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587026624,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587281616,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1457",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587281616,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587570352,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:781",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce",
        "net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/ioctl.c:load_link_ksettings_from_user",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587570352,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496098704,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1197",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/perf_event.c:__armv8pmu_probe_pmu",
        "arch/arm64/kernel/perf_event.c:__armv8pmu_probe_pmu",
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496098704,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290343568,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1197",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290343568,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275166842,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1197",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275166842,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193600,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1197",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193600,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584128816,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1197",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128816,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584177360,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1197",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584177360,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```

```json
{
  "name": "bitmap_from_arr32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584281696,
      "name": "bitmap_from_arr32",
      "external": true,
      "loc": "lib/bitmap.c:1197",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584281696,
      "name": "bitmap_from_arr32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void bitmap_from_arr32(long unsigned int * bitmap, const u32 * buf, unsigned int nbits)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
