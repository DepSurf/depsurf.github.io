# Function: <code>adjust_dev_dax_range</code>

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
int adjust_dev_dax_range(struct dev_dax * dev_dax, struct resource * res, resource_size_t size)
```

```json
{
  "name": "adjust_dev_dax_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587442896,
      "name": "adjust_dev_dax_range",
      "external": false,
      "loc": "drivers/dax/bus.c:814",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587442896,
      "name": "adjust_dev_dax_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int adjust_dev_dax_range(struct dev_dax * dev_dax, struct resource * res, resource_size_t size)
```

```json
{
  "name": "adjust_dev_dax_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587324608,
      "name": "adjust_dev_dax_range",
      "external": false,
      "loc": "drivers/dax/bus.c:815",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587324608,
      "name": "adjust_dev_dax_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int adjust_dev_dax_range(struct dev_dax * dev_dax, struct resource * res, resource_size_t size)
```

```json
{
  "name": "adjust_dev_dax_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_dev_dax_range",
      "external": false,
      "loc": "drivers/dax/bus.c:813",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587891872,
      "name": "adjust_dev_dax_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071592524069,
      "name": "adjust_dev_dax_range.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int adjust_dev_dax_range(struct dev_dax * dev_dax, struct resource * res, resource_size_t size)
```

```json
{
  "name": "adjust_dev_dax_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_dev_dax_range",
      "external": false,
      "loc": "drivers/dax/bus.c:843",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589241104,
      "name": "adjust_dev_dax_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071594395444,
      "name": "adjust_dev_dax_range.cold",
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
int adjust_dev_dax_range(struct dev_dax * dev_dax, struct resource * res, resource_size_t size)
```

```json
{
  "name": "adjust_dev_dax_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_dev_dax_range",
      "external": false,
      "loc": "drivers/dax/bus.c:843",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590800224,
      "name": "adjust_dev_dax_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071596258740,
      "name": "adjust_dev_dax_range.cold",
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
int adjust_dev_dax_range(struct dev_dax * dev_dax, struct resource * res, resource_size_t size)
```

```json
{
  "name": "adjust_dev_dax_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_dev_dax_range",
      "external": false,
      "loc": "drivers/dax/bus.c:873",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591141152,
      "name": "adjust_dev_dax_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071596786819,
      "name": "adjust_dev_dax_range.cold",
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
int adjust_dev_dax_range(struct dev_dax * dev_dax, struct resource * res, resource_size_t size)
```

```json
{
  "name": "adjust_dev_dax_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_dev_dax_range",
      "external": false,
      "loc": "drivers/dax/bus.c:874",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591486848,
      "name": "adjust_dev_dax_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071597695754,
      "name": "adjust_dev_dax_range.cold",
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
int adjust_dev_dax_range(struct dev_dax * dev_dax, struct resource * res, resource_size_t size)
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
