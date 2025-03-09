# Function: <code>device_link_drop_managed</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586166529,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:638",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void device_link_drop_managed(struct device_link * link)
```

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919952,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:846",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver",
        "drivers/base/core.c:device_links_driver_bound"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919952,
      "name": "device_link_drop_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void device_link_drop_managed(struct device_link * link)
```

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587004848,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:1107",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver",
        "drivers/base/core.c:device_links_driver_bound"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004848,
      "name": "device_link_drop_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void device_link_drop_managed(struct device_link * link)
```

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586887360,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:1144",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/core.c:device_links_force_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586887360,
      "name": "device_link_drop_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void device_link_drop_managed(struct device_link * link)
```

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587449088,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:1159",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/core.c:device_links_force_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449088,
      "name": "device_link_drop_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void device_link_drop_managed(struct device_link * link)
```

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588766400,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:1171",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/core.c:device_links_force_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588766400,
      "name": "device_link_drop_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void device_link_drop_managed(struct device_link * link)
```

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590257568,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:1278",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/core.c:device_links_force_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590257568,
      "name": "device_link_drop_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void device_link_drop_managed(struct device_link * link)
```

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590576832,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:1217",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/core.c:device_links_force_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590576832,
      "name": "device_link_drop_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void device_link_drop_managed(struct device_link * link)
```

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590935232,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:1220",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver",
        "drivers/base/core.c:device_links_driver_bound",
        "drivers/base/core.c:device_links_force_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590935232,
      "name": "device_link_drop_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void device_link_drop_managed(struct device_link * link)
```

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498949536,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:638",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498949536,
      "name": "device_link_drop_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void device_link_drop_managed(struct device_link * link)
```

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231521144,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:638",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231521144,
      "name": "device_link_drop_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void device_link_drop_managed(struct device_link * link)
```

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292090896,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:638",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292090896,
      "name": "device_link_drop_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276343286,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:638",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585926897,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:638",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585776033,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:638",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586116545,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:638",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_link_drop_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586225153,
      "name": "device_link_drop_managed",
      "external": false,
      "loc": "drivers/base/core.c:638",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_links_driver_cleanup",
        "drivers/base/core.c:__device_links_no_driver"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void device_link_drop_managed(struct device_link * link)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void device_link_drop_managed(struct device_link * link)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void device_link_drop_managed(struct device_link * link)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void device_link_drop_managed(struct device_link * link)
```
</details>
</li>
</ul>
