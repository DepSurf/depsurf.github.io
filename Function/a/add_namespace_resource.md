# Function: <code>add_namespace_resource</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585275284,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1965",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585360034,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2142",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585785215,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2151",
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
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586032043,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2145",
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
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586171199,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2170",
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
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586408955,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2177",
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
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586555787,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2177",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int add_namespace_resource(struct nd_region * nd_region, struct nd_namespace_label * nd_label, struct device * * devs, int count)
```

```json
{
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2218",
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
      "addr": 18446744071587340816,
      "name": "add_namespace_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071587344487,
      "name": "add_namespace_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int add_namespace_resource(struct nd_region * nd_region, struct nd_namespace_label * nd_label, struct device * * devs, int count)
```

```json
{
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2218",
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
      "addr": 18446744071587402544,
      "name": "add_namespace_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071591517270,
      "name": "add_namespace_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int add_namespace_resource(struct nd_region * nd_region, struct nd_namespace_label * nd_label, struct device * * devs, int count)
```

```json
{
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2218",
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
      "addr": 18446744071587284288,
      "name": "add_namespace_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071591459247,
      "name": "add_namespace_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int add_namespace_resource(struct nd_region * nd_region, struct nd_namespace_label * nd_label, struct device * * devs, int count)
```

```json
{
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2211",
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
      "addr": 18446744071587851120,
      "name": "add_namespace_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446744071592522445,
      "name": "add_namespace_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589200086,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1894",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590755073,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1884",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591096484,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1884",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591441524,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1895",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499445604,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2177",
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
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292703456,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2177",
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
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276669400,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2177",
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
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586246267,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2177",
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
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586064635,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2177",
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
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586503755,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2177",
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
  "name": "add_namespace_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586615499,
      "name": "add_namespace_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:2177",
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int add_namespace_resource(struct nd_region * nd_region, struct nd_namespace_label * nd_label, struct device * * devs, int count)
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
int add_namespace_resource(struct nd_region * nd_region, struct nd_namespace_label * nd_label, struct device * * devs, int count)
```
</details>
</li>
</ul>
