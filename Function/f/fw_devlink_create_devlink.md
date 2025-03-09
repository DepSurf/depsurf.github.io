# Function: <code>fw_devlink_create_devlink</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int fw_devlink_create_devlink(struct device * con, struct fwnode_handle * sup_handle, u32 flags)
```

```json
{
  "name": "fw_devlink_create_devlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587012656,
      "name": "fw_devlink_create_devlink",
      "external": false,
      "loc": "drivers/base/core.c:1528",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:__fw_devlink_link_to_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587012656,
      "name": "fw_devlink_create_devlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int fw_devlink_create_devlink(struct device * con, struct fwnode_handle * sup_handle, u32 flags)
```

```json
{
  "name": "fw_devlink_create_devlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_devlink_create_devlink",
      "external": false,
      "loc": "drivers/base/core.c:1716",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:fw_devlink_link_device",
        "drivers/base/core.c:fw_devlink_link_device",
        "drivers/base/core.c:__fw_devlink_link_to_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586895952,
      "name": "fw_devlink_create_devlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    },
    {
      "addr": 18446744071591429640,
      "name": "fw_devlink_create_devlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int fw_devlink_create_devlink(struct device * con, struct fwnode_handle * sup_handle, u32 flags)
```

```json
{
  "name": "fw_devlink_create_devlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_devlink_create_devlink",
      "external": false,
      "loc": "drivers/base/core.c:1731",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:__fw_devlink_link_to_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587457856,
      "name": "fw_devlink_create_devlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071592487848,
      "name": "fw_devlink_create_devlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int fw_devlink_create_devlink(struct device * con, struct fwnode_handle * sup_handle, u32 flags)
```

```json
{
  "name": "fw_devlink_create_devlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_devlink_create_devlink",
      "external": false,
      "loc": "drivers/base/core.c:1743",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:__fw_devlink_link_to_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588776832,
      "name": "fw_devlink_create_devlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071594357494,
      "name": "fw_devlink_create_devlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
int fw_devlink_create_devlink(struct device * con, struct fwnode_handle * sup_handle, struct fwnode_link * link)
```

```json
{
  "name": "fw_devlink_create_devlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590270096,
      "name": "fw_devlink_create_devlink",
      "external": false,
      "loc": "drivers/base/core.c:2024",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:__fw_devlink_link_to_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590270096,
      "name": "fw_devlink_create_devlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
int fw_devlink_create_devlink(struct device * con, struct fwnode_handle * sup_handle, struct fwnode_link * link)
```

```json
{
  "name": "fw_devlink_create_devlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590590544,
      "name": "fw_devlink_create_devlink",
      "external": false,
      "loc": "drivers/base/core.c:2026",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:__fw_devlink_link_to_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590590544,
      "name": "fw_devlink_create_devlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
int fw_devlink_create_devlink(struct device * con, struct fwnode_handle * sup_handle, struct fwnode_link * link)
```

```json
{
  "name": "fw_devlink_create_devlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590949264,
      "name": "fw_devlink_create_devlink",
      "external": false,
      "loc": "drivers/base/core.c:2035",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:__fw_devlink_link_to_suppliers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590949264,
      "name": "fw_devlink_create_devlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int fw_devlink_create_devlink(struct device * con, struct fwnode_handle * sup_handle, u32 flags)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fwnode_link * link</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
