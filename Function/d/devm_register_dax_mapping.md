# Function: <code>devm_register_dax_mapping</code>

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
int devm_register_dax_mapping(struct dev_dax * dev_dax, int range_id)
```

```json
{
  "name": "devm_register_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587444496,
      "name": "devm_register_dax_mapping",
      "external": false,
      "loc": "drivers/dax/bus.c:712",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444496,
      "name": "devm_register_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int devm_register_dax_mapping(struct dev_dax * dev_dax, int range_id)
```

```json
{
  "name": "devm_register_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587326064,
      "name": "devm_register_dax_mapping",
      "external": false,
      "loc": "drivers/dax/bus.c:713",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587326064,
      "name": "devm_register_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int devm_register_dax_mapping(struct dev_dax * dev_dax, int range_id)
```

```json
{
  "name": "devm_register_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_register_dax_mapping",
      "external": false,
      "loc": "drivers/dax/bus.c:711",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587892912,
      "name": "devm_register_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    },
    {
      "addr": 18446744071592524097,
      "name": "devm_register_dax_mapping.cold",
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
int devm_register_dax_mapping(struct dev_dax * dev_dax, int range_id)
```

```json
{
  "name": "devm_register_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_register_dax_mapping",
      "external": false,
      "loc": "drivers/dax/bus.c:741",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589242192,
      "name": "devm_register_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
    },
    {
      "addr": 18446744071594395472,
      "name": "devm_register_dax_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int devm_register_dax_mapping(struct dev_dax * dev_dax, int range_id)
```

```json
{
  "name": "devm_register_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_register_dax_mapping",
      "external": false,
      "loc": "drivers/dax/bus.c:741",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590801392,
      "name": "devm_register_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
    },
    {
      "addr": 18446744071596258768,
      "name": "devm_register_dax_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int devm_register_dax_mapping(struct dev_dax * dev_dax, int range_id)
```

```json
{
  "name": "devm_register_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_register_dax_mapping",
      "external": false,
      "loc": "drivers/dax/bus.c:770",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591143136,
      "name": "devm_register_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071596786860,
      "name": "devm_register_dax_mapping.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int devm_register_dax_mapping(struct dev_dax * dev_dax, int range_id)
```

```json
{
  "name": "devm_register_dax_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_register_dax_mapping",
      "external": false,
      "loc": "drivers/dax/bus.c:771",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591488368,
      "name": "devm_register_dax_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
    },
    {
      "addr": 18446744071597695795,
      "name": "devm_register_dax_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int devm_register_dax_mapping(struct dev_dax * dev_dax, int range_id)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
