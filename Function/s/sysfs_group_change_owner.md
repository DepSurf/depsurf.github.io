# Function: <code>sysfs_group_change_owner</code>

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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582548416,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:511",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582548416,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582854608,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:517",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:queue_change_owner",
        "net/core/net-sysfs.c:queue_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582854608,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582927664,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:517",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:queue_change_owner",
        "net/core/net-sysfs.c:queue_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582927664,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582955312,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:517",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582955312,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583290560,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:517",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290560,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583797008,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:516",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583797008,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584417312,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:516",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417312,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584645904,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:520",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584645904,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584878288,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:520",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584878288,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494187616,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:511",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494187616,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227623648,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:511",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227623648,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287877168,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:511",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287877168,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273651082,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:511",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273651082,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582517152,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:511",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582517152,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582454320,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:511",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454320,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582507632,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:511",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582507632,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "sysfs_group_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588528,
      "name": "sysfs_group_change_owner",
      "external": true,
      "loc": "fs/sysfs/group.c:511",
      "file": "fs/sysfs/group.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/group.c:sysfs_groups_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "drivers/base/power/sysfs.c:dpm_sysfs_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner",
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588528,
      "name": "sysfs_group_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int sysfs_group_change_owner(struct kobject * kobj, const struct attribute_group * grp, kuid_t kuid, kgid_t kgid)
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
