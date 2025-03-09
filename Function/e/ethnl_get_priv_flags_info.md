# Function: <code>ethnl_get_priv_flags_info</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ethnl_get_priv_flags_info(struct net_device * dev, unsigned int * count, const char[32] * * names)
```

```json
{
  "name": "ethnl_get_priv_flags_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589897136,
      "name": "ethnl_get_priv_flags_info",
      "external": false,
      "loc": "net/ethtool/privflags.c:28",
      "file": "net/ethtool/privflags.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data",
        "net/ethtool/privflags.c:privflags_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589897136,
      "name": "ethnl_get_priv_flags_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int ethnl_get_priv_flags_info(struct net_device * dev, unsigned int * count, const char[32] * * names)
```

```json
{
  "name": "ethnl_get_priv_flags_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589936144,
      "name": "ethnl_get_priv_flags_info",
      "external": false,
      "loc": "net/ethtool/privflags.c:26",
      "file": "net/ethtool/privflags.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data",
        "net/ethtool/privflags.c:privflags_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589936144,
      "name": "ethnl_get_priv_flags_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int ethnl_get_priv_flags_info(struct net_device * dev, unsigned int * count, const char[32] * * names)
```

```json
{
  "name": "ethnl_get_priv_flags_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589844496,
      "name": "ethnl_get_priv_flags_info",
      "external": false,
      "loc": "net/ethtool/privflags.c:26",
      "file": "net/ethtool/privflags.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data",
        "net/ethtool/privflags.c:privflags_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589844496,
      "name": "ethnl_get_priv_flags_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int ethnl_get_priv_flags_info(struct net_device * dev, unsigned int * count, const char[32] * * names)
```

```json
{
  "name": "ethnl_get_priv_flags_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_get_priv_flags_info",
      "external": false,
      "loc": "net/ethtool/privflags.c:26",
      "file": "net/ethtool/privflags.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590606928,
      "name": "ethnl_get_priv_flags_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071592712853,
      "name": "ethnl_get_priv_flags_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int ethnl_get_priv_flags_info(struct net_device * dev, unsigned int * count, const char[32] * * names)
```

```json
{
  "name": "ethnl_get_priv_flags_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_get_priv_flags_info",
      "external": false,
      "loc": "net/ethtool/privflags.c:26",
      "file": "net/ethtool/privflags.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592227536,
      "name": "ethnl_get_priv_flags_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071594598928,
      "name": "ethnl_get_priv_flags_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ethnl_get_priv_flags_info(struct net_device * dev, unsigned int * count, const char[32] * * names)
```

```json
{
  "name": "ethnl_get_priv_flags_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_get_priv_flags_info",
      "external": false,
      "loc": "net/ethtool/privflags.c:26",
      "file": "net/ethtool/privflags.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594059280,
      "name": "ethnl_get_priv_flags_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071596334820,
      "name": "ethnl_get_priv_flags_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ethnl_get_priv_flags_info(struct net_device * dev, unsigned int * count, const char[32] * * names)
```

```json
{
  "name": "ethnl_get_priv_flags_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_get_priv_flags_info",
      "external": false,
      "loc": "net/ethtool/privflags.c:26",
      "file": "net/ethtool/privflags.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594437888,
      "name": "ethnl_get_priv_flags_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071596863793,
      "name": "ethnl_get_priv_flags_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ethnl_get_priv_flags_info(struct net_device * dev, unsigned int * count, const char[32] * * names)
```

```json
{
  "name": "ethnl_get_priv_flags_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_get_priv_flags_info",
      "external": false,
      "loc": "net/ethtool/privflags.c:26",
      "file": "net/ethtool/privflags.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595240240,
      "name": "ethnl_get_priv_flags_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071597788866,
      "name": "ethnl_get_priv_flags_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ethnl_get_priv_flags_info(struct net_device * dev, unsigned int * count, const char[32] * * names)
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
