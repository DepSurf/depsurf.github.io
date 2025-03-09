# Function: <code>alloc_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579396608,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:188",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:release_mem_region_adjustable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396608,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579408976,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:197",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408976,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579429280,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:197",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429280,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579416944,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:197",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416944,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444976,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:197",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444976,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579459760,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:164",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579459760,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579493408,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:164",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493408,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579511200,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511200,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579537264,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537264,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579567232,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:__reserve_region_with_split",
        "kernel/resource.c:__reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567232,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548576,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:__reserve_region_with_split",
        "kernel/resource.c:__reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548576,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554416,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:164",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554416,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626976,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:164",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626976,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579722053,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
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
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579850758,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
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
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579900998,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
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
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579939751,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490680208,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490680208,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224752112,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224752112,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
void alloc_resource(struct pci_dev * dev, int idx)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302423896,
      "name": "alloc_resource",
      "external": false,
      "loc": "arch/powerpc/kernel/pci-common.c:1231",
      "file": "arch/powerpc/kernel/pci-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/pci-common.c:pcibios_allocate_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283507504,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283507504,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271417162,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271417162,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579510928,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510928,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579439728,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439728,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579510848,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510848,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
struct resource * alloc_resource(gfp_t flags)
```

```json
{
  "name": "alloc_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579543728,
      "name": "alloc_resource",
      "external": false,
      "loc": "kernel/resource.c:165",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543728,
      "name": "alloc_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
struct resource * alloc_resource(gfp_t flags)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev * dev</code>
</li>
<li>
<b>Param added. </b>
<code>int idx</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct resource *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
