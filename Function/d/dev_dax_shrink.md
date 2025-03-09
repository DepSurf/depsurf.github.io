# Function: <code>dev_dax_shrink</code>

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
int dev_dax_shrink(struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587447680,
      "name": "dev_dax_shrink",
      "external": false,
      "loc": "drivers/dax/bus.c:867",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447680,
      "name": "dev_dax_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int dev_dax_shrink(struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587329376,
      "name": "dev_dax_shrink",
      "external": false,
      "loc": "drivers/dax/bus.c:868",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587329376,
      "name": "dev_dax_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int dev_dax_shrink(struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_dax_shrink",
      "external": false,
      "loc": "drivers/dax/bus.c:866",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587896224,
      "name": "dev_dax_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    },
    {
      "addr": 18446744071592524137,
      "name": "dev_dax_shrink.cold",
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
int dev_dax_shrink(struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_dax_shrink",
      "external": false,
      "loc": "drivers/dax/bus.c:896",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245552,
      "name": "dev_dax_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    },
    {
      "addr": 18446744071594395529,
      "name": "dev_dax_shrink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int dev_dax_shrink(struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_dax_shrink",
      "external": false,
      "loc": "drivers/dax/bus.c:896",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590804976,
      "name": "dev_dax_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    },
    {
      "addr": 18446744071596258825,
      "name": "dev_dax_shrink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int dev_dax_shrink(struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_dax_shrink",
      "external": false,
      "loc": "drivers/dax/bus.c:926",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591146128,
      "name": "dev_dax_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    },
    {
      "addr": 18446744071596786901,
      "name": "dev_dax_shrink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int dev_dax_shrink(struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_dax_shrink",
      "external": false,
      "loc": "drivers/dax/bus.c:927",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591492048,
      "name": "dev_dax_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    },
    {
      "addr": 18446744071597695836,
      "name": "dev_dax_shrink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int dev_dax_shrink(struct dev_dax * dev_dax, resource_size_t size)
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
