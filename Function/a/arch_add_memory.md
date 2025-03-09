# Function: <code>arch_add_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, bool for_device)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274608,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:690",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274608,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int arch_add_memory(int nid, u64 start, u64 size, bool for_device)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579273664,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:654",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273664,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int arch_add_memory(int nid, u64 start, u64 size, bool for_device)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579289104,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:644",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579289104,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int arch_add_memory(int nid, u64 start, u64 size, bool want_memblock)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579286048,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:775",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286048,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int arch_add_memory(int nid, u64 start, u64 size, bool want_memblock)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308560,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:790",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/hmm.c:hmm_devmem_pages_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308560,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int arch_add_memory(int nid, u64 start, u64 size, struct vmem_altmap * altmap, bool want_memblock)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320208,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:801",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/hmm.c:hmm_devmem_pages_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320208,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int arch_add_memory(int nid, u64 start, u64 size, struct vmem_altmap * altmap, bool want_memblock)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579344512,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:794",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344512,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579360176,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:861",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360176,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579364416,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:861",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579364416,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params * params)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391456,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:869",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391456,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params * params)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395728,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:863",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395728,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params * params)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399184,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:963",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399184,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params * params)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461440,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:964",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461440,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params * params)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579537488,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:964",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537488,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params * params)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641680,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:965",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641680,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params * params)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655728,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:965",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655728,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params * params)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689600,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:965",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:create_altmaps_and_memory_blocks",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689600,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490350008,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/arm64/mm/mmu.c:1053",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490350008,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282718272,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/powerpc/mm/mem.c:128",
      "file": "arch/powerpc/mm/mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282718272,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579360320,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:861",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360320,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291456,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:861",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291456,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579360240,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:861",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360240,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "arch_add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579368672,
      "name": "arch_add_memory",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:861",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368672,
      "name": "arch_add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool want_memblock</code>
</li>
<li>
<b>Param removed. </b>
<code>bool for_device</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap * altmap</code>
</li>
<li>
<b>Param reordered. </b>
<code>nid, start, size, want_memblock</code> ➡️ <code>nid, start, size, altmap, want_memblock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mhp_restrictions * restrictions</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vmem_altmap * altmap</code>
</li>
<li>
<b>Param removed. </b>
<code>bool want_memblock</code>
</li>
</ul>
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
<b>Param added. </b>
<code>struct mhp_params * params</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mhp_restrictions * restrictions</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions * restrictions)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions * restrictions)
```
</details>
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
