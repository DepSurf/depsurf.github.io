# Function: <code>ethnl_update_bitset32</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ethnl_update_bitset32(u32 * bitmap, unsigned int nbits, const struct nlattr * attr, ethnl_string_array_t names, struct netlink_ext_ack * extack, bool * mod)
```

```json
{
  "name": "ethnl_update_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589886757,
      "name": "ethnl_update_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:554",
      "file": "net/ethtool/bitset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_update_bitset"
      ],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_update_bitset",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/eee.c:ethnl_set_eee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589883872,
      "name": "ethnl_update_bitset32.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071589885904,
      "name": "ethnl_update_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ethnl_update_bitset32(u32 * bitmap, unsigned int nbits, const struct nlattr * attr, ethnl_string_array_t names, struct netlink_ext_ack * extack, bool * mod)
```

```json
{
  "name": "ethnl_update_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589926085,
      "name": "ethnl_update_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:552",
      "file": "net/ethtool/bitset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_update_bitset"
      ],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_update_bitset",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/eee.c:ethnl_set_eee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589923168,
      "name": "ethnl_update_bitset32.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
    },
    {
      "addr": 18446744071589925200,
      "name": "ethnl_update_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ethnl_update_bitset32(u32 * bitmap, unsigned int nbits, const struct nlattr * attr, ethnl_string_array_t names, struct netlink_ext_ack * extack, bool * mod)
```

```json
{
  "name": "ethnl_update_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589833957,
      "name": "ethnl_update_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:552",
      "file": "net/ethtool/bitset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_update_bitset"
      ],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_update_bitset",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/eee.c:ethnl_set_eee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589830992,
      "name": "ethnl_update_bitset32.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    },
    {
      "addr": 18446744071589833056,
      "name": "ethnl_update_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ethnl_update_bitset32(u32 * bitmap, unsigned int nbits, const struct nlattr * attr, ethnl_string_array_t names, struct netlink_ext_ack * extack, bool * mod)
```

```json
{
  "name": "ethnl_update_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590596869,
      "name": "ethnl_update_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:552",
      "file": "net/ethtool/bitset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_update_bitset"
      ],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_update_bitset",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/eee.c:ethnl_set_eee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590593904,
      "name": "ethnl_update_bitset32.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    },
    {
      "addr": 18446744071590595952,
      "name": "ethnl_update_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int ethnl_update_bitset32(u32 * bitmap, unsigned int nbits, const struct nlattr * attr, ethnl_string_array_t names, struct netlink_ext_ack * extack, bool * mod)
```

```json
{
  "name": "ethnl_update_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592215376,
      "name": "ethnl_update_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:552",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_update_bitset",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/eee.c:ethnl_set_eee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592215376,
      "name": "ethnl_update_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
int ethnl_update_bitset32(u32 * bitmap, unsigned int nbits, const struct nlattr * attr, ethnl_string_array_t names, struct netlink_ext_ack * extack, bool * mod)
```

```json
{
  "name": "ethnl_update_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594045328,
      "name": "ethnl_update_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:552",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_update_bitset",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/eee.c:ethnl_set_eee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594045328,
      "name": "ethnl_update_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
int ethnl_update_bitset32(u32 * bitmap, unsigned int nbits, const struct nlattr * attr, ethnl_string_array_t names, struct netlink_ext_ack * extack, bool * mod)
```

```json
{
  "name": "ethnl_update_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594423680,
      "name": "ethnl_update_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:552",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_update_bitset",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/eee.c:ethnl_set_eee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594423680,
      "name": "ethnl_update_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int ethnl_update_bitset32(u32 * bitmap, unsigned int nbits, const struct nlattr * attr, ethnl_string_array_t names, struct netlink_ext_ack * extack, bool * mod)
```

```json
{
  "name": "ethnl_update_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595225920,
      "name": "ethnl_update_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:552",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_update_bitset",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/eee.c:ethnl_set_eee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595225920,
      "name": "ethnl_update_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
int ethnl_update_bitset32(u32 * bitmap, unsigned int nbits, const struct nlattr * attr, ethnl_string_array_t names, struct netlink_ext_ack * extack, bool * mod)
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
