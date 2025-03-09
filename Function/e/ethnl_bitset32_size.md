# Function: <code>ethnl_bitset32_size</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ethnl_bitset32_size(const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_bitset32_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_bitset32_size",
      "external": true,
      "loc": "net/ethtool/bitset.c:171",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_bitset_size",
        "net/ethtool/debug.c:debug_reply_size",
        "net/ethtool/wol.c:wol_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/privflags.c:privflags_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886776,
      "name": "ethnl_bitset32_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589884336,
      "name": "ethnl_bitset32_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int ethnl_bitset32_size(const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_bitset32_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_bitset32_size",
      "external": true,
      "loc": "net/ethtool/bitset.c:171",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_bitset_size",
        "net/ethtool/debug.c:debug_reply_size",
        "net/ethtool/wol.c:wol_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/privflags.c:privflags_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_reply_size",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_reply_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591633727,
      "name": "ethnl_bitset32_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589923648,
      "name": "ethnl_bitset32_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int ethnl_bitset32_size(const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_bitset32_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_bitset32_size",
      "external": true,
      "loc": "net/ethtool/bitset.c:171",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_bitset_size",
        "net/ethtool/debug.c:debug_reply_size",
        "net/ethtool/wol.c:wol_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/privflags.c:privflags_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591577128,
      "name": "ethnl_bitset32_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589831488,
      "name": "ethnl_bitset32_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ethnl_bitset32_size(const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_bitset32_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_bitset32_size",
      "external": true,
      "loc": "net/ethtool/bitset.c:171",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_bitset_size",
        "net/ethtool/debug.c:debug_reply_size",
        "net/ethtool/wol.c:wol_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/privflags.c:privflags_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592712223,
      "name": "ethnl_bitset32_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071590594384,
      "name": "ethnl_bitset32_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int ethnl_bitset32_size(const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_bitset32_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_bitset32_size",
      "external": true,
      "loc": "net/ethtool/bitset.c:171",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_bitset_size",
        "net/ethtool/debug.c:debug_reply_size",
        "net/ethtool/wol.c:wol_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/privflags.c:privflags_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594598306,
      "name": "ethnl_bitset32_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071592213760,
      "name": "ethnl_bitset32_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int ethnl_bitset32_size(const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_bitset32_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594043632,
      "name": "ethnl_bitset32_size",
      "external": true,
      "loc": "net/ethtool/bitset.c:171",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_bitset_size",
        "net/ethtool/debug.c:debug_reply_size",
        "net/ethtool/wol.c:wol_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/privflags.c:privflags_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594043632,
      "name": "ethnl_bitset32_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int ethnl_bitset32_size(const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_bitset32_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594421936,
      "name": "ethnl_bitset32_size",
      "external": true,
      "loc": "net/ethtool/bitset.c:171",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_bitset_size",
        "net/ethtool/debug.c:debug_reply_size",
        "net/ethtool/wol.c:wol_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/privflags.c:privflags_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594421936,
      "name": "ethnl_bitset32_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int ethnl_bitset32_size(const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_bitset32_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595224176,
      "name": "ethnl_bitset32_size",
      "external": true,
      "loc": "net/ethtool/bitset.c:171",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_bitset_size",
        "net/ethtool/debug.c:debug_reply_size",
        "net/ethtool/wol.c:wol_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/features.c:features_reply_size",
        "net/ethtool/privflags.c:privflags_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/eee.c:eee_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tsinfo.c:tsinfo_reply_size",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595224176,
      "name": "ethnl_bitset32_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ethnl_bitset32_size(const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```
</details>
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
