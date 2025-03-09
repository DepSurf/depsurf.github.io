# Function: <code>create_namespace_blk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct device * * create_namespace_blk(struct nd_region * nd_region)
```

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584733312,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1757",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584733312,
      "name": "create_namespace_blk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct device * * create_namespace_blk(struct nd_region * nd_region)
```

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585085536,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1823",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585085536,
      "name": "create_namespace_blk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1403
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct device * create_namespace_blk(struct nd_region * nd_region, struct nd_namespace_label * nd_label, int count)
```

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585274272,
      "name": "create_namespace_blk",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:2003",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585274272,
      "name": "create_namespace_blk",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct device * create_namespace_blk(struct nd_region * nd_region, struct nd_namespace_label * nd_label, int count)
```

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585358800,
      "name": "create_namespace_blk",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:2180",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585358800,
      "name": "create_namespace_blk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585785429,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2189",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586032442,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2183",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586171635,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2208",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586409444,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2215",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586556137,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2215",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
struct device * create_namespace_blk(struct nd_region * nd_region, struct nd_namespace_label * nd_label, int count)
```

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587341152,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2256",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587341152,
      "name": "create_namespace_blk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
struct device * create_namespace_blk(struct nd_region * nd_region, struct nd_namespace_label * nd_label, int count)
```

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587402880,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2256",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587402880,
      "name": "create_namespace_blk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
struct device * create_namespace_blk(struct nd_region * nd_region, struct nd_namespace_label * nd_label, int count)
```

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587284624,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2256",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587284624,
      "name": "create_namespace_blk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
struct device * create_namespace_blk(struct nd_region * nd_region, struct nd_namespace_label * nd_label, int count)
```

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587851440,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2249",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587851440,
      "name": "create_namespace_blk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499445768,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2215",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292703660,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2215",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276669542,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2215",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586246617,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2215",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586064985,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2215",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586504105,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2215",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
  "name": "create_namespace_blk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586615849,
      "name": "create_namespace_blk",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2215",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nd_namespace_label * nd_label</code>
</li>
<li>
<b>Param added. </b>
<code>int count</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct device * *</code> ➡️ <code>struct device *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
struct device * create_namespace_blk(struct nd_region * nd_region, struct nd_namespace_label * nd_label, int count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct device * create_namespace_blk(struct nd_region * nd_region, struct nd_namespace_label * nd_label, int count)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct device * create_namespace_blk(struct nd_region * nd_region, struct nd_namespace_label * nd_label, int count)
```
</details>
</li>
</ul>
