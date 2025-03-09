# Function: <code>sysfs_change_owner</code>

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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582542896,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:668",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542896,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582849472,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:669",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:queue_change_owner",
        "net/core/net-sysfs.c:queue_change_owner",
        "net/core/net-sysfs.c:queue_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582849472,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922528,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:670",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:queue_change_owner",
        "net/core/net-sysfs.c:queue_change_owner",
        "net/core/net-sysfs.c:queue_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922528,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582950208,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:681",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950208,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583285440,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:681",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285440,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583790512,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:691",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790512,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584410112,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:691",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584410112,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584638672,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:691",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584638672,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584870960,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:704",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584870960,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494180552,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:668",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494180552,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227617528,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:668",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227617528,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287867472,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:668",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287867472,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273645642,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:668",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273645642,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582511632,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:668",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511632,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448800,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:668",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448800,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502112,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:668",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502112,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582720,
      "name": "sysfs_change_owner",
      "external": true,
      "loc": "fs/sysfs/file.c:668",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582720,
      "name": "sysfs_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int sysfs_change_owner(struct kobject * kobj, kuid_t kuid, kgid_t kgid)
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
