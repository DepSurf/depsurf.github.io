# Function: <code>dev_dax_resize</code>

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
ssize_t dev_dax_resize(struct dax_region * dax_region, struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_resize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587448112,
      "name": "dev_dax_resize",
      "external": false,
      "loc": "drivers/dax/bus.c:933",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587448112,
      "name": "dev_dax_resize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
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
ssize_t dev_dax_resize(struct dax_region * dax_region, struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_resize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587329792,
      "name": "dev_dax_resize",
      "external": false,
      "loc": "drivers/dax/bus.c:934",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587329792,
      "name": "dev_dax_resize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
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
ssize_t dev_dax_resize(struct dax_region * dax_region, struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_resize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_dax_resize",
      "external": false,
      "loc": "drivers/dax/bus.c:932",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587896656,
      "name": "dev_dax_resize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
    },
    {
      "addr": 18446744071592524157,
      "name": "dev_dax_resize.cold",
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
ssize_t dev_dax_resize(struct dax_region * dax_region, struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_resize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_dax_resize",
      "external": false,
      "loc": "drivers/dax/bus.c:962",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246224,
      "name": "dev_dax_resize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 870
    },
    {
      "addr": 18446744071594395550,
      "name": "dev_dax_resize.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t dev_dax_resize(struct dax_region * dax_region, struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_resize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_dax_resize",
      "external": false,
      "loc": "drivers/dax/bus.c:962",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590805680,
      "name": "dev_dax_resize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 870
    },
    {
      "addr": 18446744071596258846,
      "name": "dev_dax_resize.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t dev_dax_resize(struct dax_region * dax_region, struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_resize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_dax_resize",
      "external": false,
      "loc": "drivers/dax/bus.c:992",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591146832,
      "name": "dev_dax_resize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 855
    },
    {
      "addr": 18446744071596786922,
      "name": "dev_dax_resize.cold",
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
ssize_t dev_dax_resize(struct dax_region * dax_region, struct dev_dax * dev_dax, resource_size_t size)
```

```json
{
  "name": "dev_dax_resize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_dax_resize",
      "external": false,
      "loc": "drivers/dax/bus.c:993",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591492752,
      "name": "dev_dax_resize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 855
    },
    {
      "addr": 18446744071597695857,
      "name": "dev_dax_resize.cold",
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
ssize_t dev_dax_resize(struct dax_region * dax_region, struct dev_dax * dev_dax, resource_size_t size)
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
