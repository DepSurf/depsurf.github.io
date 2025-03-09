# Function: <code>__walk_iomem_res_desc</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __walk_iomem_res_desc(struct resource * res, long unsigned int desc, bool first_level_children_only, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444144,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:405",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444144,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __walk_iomem_res_desc(struct resource * res, long unsigned int desc, bool first_level_children_only, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579458832,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:372",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458832,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579492368,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:379",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492368,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510128,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:395",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510128,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536192,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:395",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536192,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579570314,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:395",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579551722,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:400",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579556330,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:387",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579628906,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:387",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579724122,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:374",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
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
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579853674,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:374",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
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
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579903930,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:374",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
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
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579943146,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:374",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490682464,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:395",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490682464,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224753672,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:395",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224753672,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283505504,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:395",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283505504,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271416492,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:395",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271416492,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509856,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:395",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509856,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438656,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:395",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438656,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509776,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:395",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509776,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "__walk_iomem_res_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542656,
      "name": "__walk_iomem_res_desc",
      "external": false,
      "loc": "kernel/resource.c:395",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542656,
      "name": "__walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __walk_iomem_res_desc(struct resource * res, long unsigned int desc, bool first_level_children_only, void * arg, int (*)(struct resource *, void *) func)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>resource_size_t start</code>
</li>
<li>
<b>Param added. </b>
<code>resource_size_t end</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param added. </b>
<code>bool first_lvl</code>
</li>
<li>
<b>Param removed. </b>
<code>struct resource * res</code>
</li>
<li>
<b>Param removed. </b>
<code>bool first_level_children_only</code>
</li>
<li>
<b>Param reordered. </b>
<code>res, desc, first_level_children_only, arg, func</code> ➡️ <code>start, end, flags, desc, first_lvl, arg, func</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __walk_iomem_res_desc(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, void * arg, int (*)(struct resource *, void *) func)
```
</details>
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
