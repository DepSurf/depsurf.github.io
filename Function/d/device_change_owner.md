# Function: <code>device_change_owner</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586159584,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:3231",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159584,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586917312,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:3699",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586917312,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587001936,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:4111",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587001936,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586884288,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:4338",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884288,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587445888,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:4403",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587445888,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588762752,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:4437",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588762752,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590251696,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:4656",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590251696,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590571744,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:4662",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590571744,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590930144,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:4675",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590930144,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498954352,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:3231",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498954352,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231525788,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:3231",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231525788,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292097680,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:3231",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292097680,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276336836,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:3231",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276336836,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585919952,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:3231",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585919952,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585769088,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:3231",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585769088,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586109600,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:3231",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586109600,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "device_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586218208,
      "name": "device_change_owner",
      "external": true,
      "loc": "drivers/base/core.c:3231",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586218208,
      "name": "device_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int device_change_owner(struct device * dev, kuid_t kuid, kgid_t kgid)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
