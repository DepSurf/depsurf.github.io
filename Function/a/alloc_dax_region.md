# Function: <code>alloc_dax_region</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct resource * res, int target_node, unsigned int align, long unsigned int pfn_flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586448352,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:228",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586448352,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct resource * res, int target_node, unsigned int align, long unsigned int pfn_flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586596320,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:228",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586596320,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct resource * res, int target_node, unsigned int align, long long unsigned int pfn_flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587381584,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:228",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587381584,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct range * range, int target_node, unsigned int align, long unsigned int flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587446848,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:543",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587446848,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct range * range, int target_node, unsigned int align, long unsigned int flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587328560,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:544",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587328560,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct range * range, int target_node, unsigned int align, long unsigned int flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587895424,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:542",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587895424,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct range * range, int target_node, unsigned int align, long unsigned int flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589244848,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:572",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589244848,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct range * range, int target_node, unsigned int align, long unsigned int flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590804240,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:572",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590804240,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct range * range, int target_node, unsigned int align, long unsigned int flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591144592,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:601",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591144592,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct range * range, int target_node, unsigned int align, long unsigned int flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591490672,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:602",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591490672,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct resource * res, int target_node, unsigned int align, long unsigned int pfn_flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499478448,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:228",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499478448,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct resource * res, int target_node, unsigned int align, long unsigned int pfn_flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231953416,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:228",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231953416,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct resource * res, int target_node, unsigned int align, long unsigned int pfn_flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292759232,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:228",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292759232,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct resource * res, int target_node, unsigned int align, long unsigned int pfn_flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276699046,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:228",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276699046,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct resource * res, int target_node, unsigned int align, long unsigned int pfn_flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586286800,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:228",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586286800,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct resource * res, int target_node, unsigned int align, long unsigned int pfn_flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586124288,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:228",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/pmem/core.c:__dax_pmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586124288,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct resource * res, int target_node, unsigned int align, long unsigned int pfn_flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586544288,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:228",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586544288,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct resource * res, int target_node, unsigned int align, long unsigned int pfn_flags)
```

```json
{
  "name": "alloc_dax_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586656064,
      "name": "alloc_dax_region",
      "external": true,
      "loc": "drivers/dax/bus.c:228",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586656064,
      "name": "alloc_dax_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct dax_region * alloc_dax_region(struct device * parent, int region_id, struct resource * res, int target_node, unsigned int align, long unsigned int pfn_flags)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int pfn_flags</code> ➡️ <code>long long unsigned int pfn_flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct range * range</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct resource * res</code>
</li>
<li>
<b>Param removed. </b>
<code>long long unsigned int pfn_flags</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
