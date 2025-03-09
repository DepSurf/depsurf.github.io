# Function: <code>ethnl_put_bitset32</code>

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
int ethnl_put_bitset32(struct sk_buff * skb, int attrtype, const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_put_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_put_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:232",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_put_bitset",
        "net/ethtool/debug.c:debug_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/privflags.c:privflags_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886788,
      "name": "ethnl_put_bitset32.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589884736,
      "name": "ethnl_put_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 987
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
int ethnl_put_bitset32(struct sk_buff * skb, int attrtype, const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_put_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_put_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:232",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_put_bitset",
        "net/ethtool/debug.c:debug_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/privflags.c:privflags_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591633739,
      "name": "ethnl_put_bitset32.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589924048,
      "name": "ethnl_put_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 969
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
int ethnl_put_bitset32(struct sk_buff * skb, int attrtype, const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_put_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_put_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:232",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_put_bitset",
        "net/ethtool/debug.c:debug_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/privflags.c:privflags_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591577140,
      "name": "ethnl_put_bitset32.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589831888,
      "name": "ethnl_put_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 965
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
int ethnl_put_bitset32(struct sk_buff * skb, int attrtype, const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_put_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_put_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:232",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_put_bitset",
        "net/ethtool/debug.c:debug_fill_reply",
        "net/ethtool/wol.c:wol_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/privflags.c:privflags_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592712235,
      "name": "ethnl_put_bitset32.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071590594784,
      "name": "ethnl_put_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 976
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
int ethnl_put_bitset32(struct sk_buff * skb, int attrtype, const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_put_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_put_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:232",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_put_bitset",
        "net/ethtool/debug.c:debug_fill_reply",
        "net/ethtool/wol.c:wol_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/privflags.c:privflags_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594598318,
      "name": "ethnl_put_bitset32.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071592214160,
      "name": "ethnl_put_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 987
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
int ethnl_put_bitset32(struct sk_buff * skb, int attrtype, const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_put_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594044064,
      "name": "ethnl_put_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:232",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_put_bitset",
        "net/ethtool/debug.c:debug_fill_reply",
        "net/ethtool/wol.c:wol_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/privflags.c:privflags_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594044064,
      "name": "ethnl_put_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 999
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
int ethnl_put_bitset32(struct sk_buff * skb, int attrtype, const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_put_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594422416,
      "name": "ethnl_put_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:232",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_put_bitset",
        "net/ethtool/debug.c:debug_fill_reply",
        "net/ethtool/wol.c:wol_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/privflags.c:privflags_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594422416,
      "name": "ethnl_put_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1002
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
int ethnl_put_bitset32(struct sk_buff * skb, int attrtype, const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
```

```json
{
  "name": "ethnl_put_bitset32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595224656,
      "name": "ethnl_put_bitset32",
      "external": true,
      "loc": "net/ethtool/bitset.c:232",
      "file": "net/ethtool/bitset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/bitset.c:ethnl_put_bitset",
        "net/ethtool/debug.c:debug_fill_reply",
        "net/ethtool/wol.c:wol_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/features.c:features_fill_reply",
        "net/ethtool/privflags.c:privflags_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/eee.c:eee_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tsinfo.c:tsinfo_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595224656,
      "name": "ethnl_put_bitset32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1002
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
int ethnl_put_bitset32(struct sk_buff * skb, int attrtype, const u32 * val, const u32 * mask, unsigned int nbits, ethnl_string_array_t names, bool compact)
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
