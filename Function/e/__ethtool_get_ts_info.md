# Function: <code>__ethtool_get_ts_info</code>

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
int __ethtool_get_ts_info(struct net_device * dev, struct ethtool_ts_info * info)
```

```json
{
  "name": "__ethtool_get_ts_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589877600,
      "name": "__ethtool_get_ts_info",
      "external": true,
      "loc": "net/ethtool/common.c:357",
      "file": "net/ethtool/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589877600,
      "name": "__ethtool_get_ts_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __ethtool_get_ts_info(struct net_device * dev, struct ethtool_ts_info * info)
```

```json
{
  "name": "__ethtool_get_ts_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589916912,
      "name": "__ethtool_get_ts_info",
      "external": true,
      "loc": "net/ethtool/common.c:384",
      "file": "net/ethtool/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589916912,
      "name": "__ethtool_get_ts_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __ethtool_get_ts_info(struct net_device * dev, struct ethtool_ts_info * info)
```

```json
{
  "name": "__ethtool_get_ts_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589824496,
      "name": "__ethtool_get_ts_info",
      "external": true,
      "loc": "net/ethtool/common.c:537",
      "file": "net/ethtool/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589824496,
      "name": "__ethtool_get_ts_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __ethtool_get_ts_info(struct net_device * dev, struct ethtool_ts_info * info)
```

```json
{
  "name": "__ethtool_get_ts_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590586592,
      "name": "__ethtool_get_ts_info",
      "external": true,
      "loc": "net/ethtool/common.c:539",
      "file": "net/ethtool/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/common.c:ethtool_get_phc_vclocks",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590586592,
      "name": "__ethtool_get_ts_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __ethtool_get_ts_info(struct net_device * dev, struct ethtool_ts_info * info)
```

```json
{
  "name": "__ethtool_get_ts_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592205920,
      "name": "__ethtool_get_ts_info",
      "external": true,
      "loc": "net/ethtool/common.c:543",
      "file": "net/ethtool/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/common.c:ethtool_get_phc_vclocks",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592205920,
      "name": "__ethtool_get_ts_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int __ethtool_get_ts_info(struct net_device * dev, struct ethtool_ts_info * info)
```

```json
{
  "name": "__ethtool_get_ts_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594035360,
      "name": "__ethtool_get_ts_info",
      "external": true,
      "loc": "net/ethtool/common.c:624",
      "file": "net/ethtool/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/common.c:ethtool_get_phc_vclocks",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594035360,
      "name": "__ethtool_get_ts_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int __ethtool_get_ts_info(struct net_device * dev, struct ethtool_ts_info * info)
```

```json
{
  "name": "__ethtool_get_ts_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594413152,
      "name": "__ethtool_get_ts_info",
      "external": true,
      "loc": "net/ethtool/common.c:632",
      "file": "net/ethtool/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/common.c:ethtool_get_phc_vclocks",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594413152,
      "name": "__ethtool_get_ts_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int __ethtool_get_ts_info(struct net_device * dev, struct ethtool_ts_info * info)
```

```json
{
  "name": "__ethtool_get_ts_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595215568,
      "name": "__ethtool_get_ts_info",
      "external": true,
      "loc": "net/ethtool/common.c:632",
      "file": "net/ethtool/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/common.c:ethtool_get_ts_info_by_layer",
        "net/ethtool/common.c:ethtool_get_phc_vclocks",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595215568,
      "name": "__ethtool_get_ts_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int __ethtool_get_ts_info(struct net_device * dev, struct ethtool_ts_info * info)
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
