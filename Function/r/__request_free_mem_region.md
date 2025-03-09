# Function: <code>__request_free_mem_region</code>

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
  "name": "__request_free_mem_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579538032,
      "name": "__request_free_mem_region",
      "external": false,
      "loc": "kernel/resource.c:1647",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:request_free_mem_region",
        "kernel/resource.c:devm_request_free_mem_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538032,
      "name": "__request_free_mem_region.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct resource * __request_free_mem_region(struct device * dev, struct resource * base, long unsigned int size, const char * name)
```

```json
{
  "name": "__request_free_mem_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568336,
      "name": "__request_free_mem_region",
      "external": false,
      "loc": "kernel/resource.c:1652",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:request_free_mem_region",
        "kernel/resource.c:devm_request_free_mem_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568336,
      "name": "__request_free_mem_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct resource * __request_free_mem_region(struct device * dev, struct resource * base, long unsigned int size, const char * name)
```

```json
{
  "name": "__request_free_mem_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549696,
      "name": "__request_free_mem_region",
      "external": false,
      "loc": "kernel/resource.c:1725",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:request_free_mem_region",
        "kernel/resource.c:devm_request_free_mem_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549696,
      "name": "__request_free_mem_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct resource * __request_free_mem_region(struct device * dev, struct resource * base, long unsigned int size, const char * name)
```

```json
{
  "name": "__request_free_mem_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554880,
      "name": "__request_free_mem_region",
      "external": false,
      "loc": "kernel/resource.c:1778",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:request_free_mem_region",
        "kernel/resource.c:devm_request_free_mem_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554880,
      "name": "__request_free_mem_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
struct resource * __request_free_mem_region(struct device * dev, struct resource * base, long unsigned int size, const char * name)
```

```json
{
  "name": "__request_free_mem_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579627456,
      "name": "__request_free_mem_region",
      "external": false,
      "loc": "kernel/resource.c:1778",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:request_free_mem_region",
        "kernel/resource.c:devm_request_free_mem_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627456,
      "name": "__request_free_mem_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
struct resource * __request_free_mem_region(struct device * dev, struct resource * base, long unsigned int size, const char * name)
```

```json
{
  "name": "__request_free_mem_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579721952,
      "name": "__request_free_mem_region",
      "external": false,
      "loc": "kernel/resource.c:1777",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:request_free_mem_region",
        "kernel/resource.c:devm_request_free_mem_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721952,
      "name": "__request_free_mem_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    }
  ]
}
```
</details>
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__request_free_mem_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283508656,
      "name": "__request_free_mem_region",
      "external": false,
      "loc": "kernel/resource.c:1647",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:request_free_mem_region",
        "kernel/resource.c:devm_request_free_mem_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283508656,
      "name": "__request_free_mem_region.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__request_free_mem_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579511696,
      "name": "__request_free_mem_region",
      "external": false,
      "loc": "kernel/resource.c:1647",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:request_free_mem_region",
        "kernel/resource.c:devm_request_free_mem_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511696,
      "name": "__request_free_mem_region.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__request_free_mem_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579440496,
      "name": "__request_free_mem_region",
      "external": false,
      "loc": "kernel/resource.c:1647",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:request_free_mem_region",
        "kernel/resource.c:devm_request_free_mem_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579440496,
      "name": "__request_free_mem_region.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__request_free_mem_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579511616,
      "name": "__request_free_mem_region",
      "external": false,
      "loc": "kernel/resource.c:1647",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:request_free_mem_region",
        "kernel/resource.c:devm_request_free_mem_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511616,
      "name": "__request_free_mem_region.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__request_free_mem_region",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579544512,
      "name": "__request_free_mem_region",
      "external": false,
      "loc": "kernel/resource.c:1647",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:request_free_mem_region",
        "kernel/resource.c:devm_request_free_mem_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544512,
      "name": "__request_free_mem_region.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct resource * __request_free_mem_region(struct device * dev, struct resource * base, long unsigned int size, const char * name)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct resource * __request_free_mem_region(struct device * dev, struct resource * base, long unsigned int size, const char * name)
```
</details>
</li>
</ul>
