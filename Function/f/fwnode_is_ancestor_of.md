# Function: <code>fwnode_is_ancestor_of</code>

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
bool fwnode_is_ancestor_of(struct fwnode_handle * test_ancestor, struct fwnode_handle * test_child)
```

```json
{
  "name": "fwnode_is_ancestor_of",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587063744,
      "name": "fwnode_is_ancestor_of",
      "external": true,
      "loc": "drivers/base/property.c:698",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587063744,
      "name": "fwnode_is_ancestor_of",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
bool fwnode_is_ancestor_of(struct fwnode_handle * test_ancestor, struct fwnode_handle * test_child)
```

```json
{
  "name": "fwnode_is_ancestor_of",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586947712,
      "name": "fwnode_is_ancestor_of",
      "external": true,
      "loc": "drivers/base/property.c:698",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:fw_devlink_link_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586947712,
      "name": "fwnode_is_ancestor_of",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
bool fwnode_is_ancestor_of(struct fwnode_handle * test_ancestor, struct fwnode_handle * test_child)
```

```json
{
  "name": "fwnode_is_ancestor_of",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587512032,
      "name": "fwnode_is_ancestor_of",
      "external": true,
      "loc": "drivers/base/property.c:699",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:fw_devlink_create_devlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587512032,
      "name": "fwnode_is_ancestor_of",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
bool fwnode_is_ancestor_of(struct fwnode_handle * ancestor, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_is_ancestor_of",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588839440,
      "name": "fwnode_is_ancestor_of",
      "external": true,
      "loc": "drivers/base/property.c:697",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:fw_devlink_create_devlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588839440,
      "name": "fwnode_is_ancestor_of",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
bool fwnode_is_ancestor_of(struct fwnode_handle * ancestor, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_is_ancestor_of",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590341056,
      "name": "fwnode_is_ancestor_of",
      "external": true,
      "loc": "drivers/base/property.c:705",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590341056,
      "name": "fwnode_is_ancestor_of",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
bool fwnode_is_ancestor_of(const struct fwnode_handle * ancestor, const struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_is_ancestor_of",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590661232,
      "name": "fwnode_is_ancestor_of",
      "external": true,
      "loc": "drivers/base/property.c:721",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590661232,
      "name": "fwnode_is_ancestor_of",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
bool fwnode_is_ancestor_of(const struct fwnode_handle * ancestor, const struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_is_ancestor_of",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591021760,
      "name": "fwnode_is_ancestor_of",
      "external": true,
      "loc": "drivers/base/property.c:785",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/core.c:fw_devlink_create_devlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591021760,
      "name": "fwnode_is_ancestor_of",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
bool fwnode_is_ancestor_of(struct fwnode_handle * test_ancestor, struct fwnode_handle * test_child)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fwnode_handle * ancestor</code>
</li>
<li>
<b>Param added. </b>
<code>struct fwnode_handle * child</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fwnode_handle * test_ancestor</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fwnode_handle * test_child</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle * ancestor</code> ➡️ <code>const struct fwnode_handle * ancestor</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle * child</code> ➡️ <code>const struct fwnode_handle * child</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
