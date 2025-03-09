# Function: <code>mem_hotplug_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587338913,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:122",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:remove_memory"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580876128,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587842148,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:142",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581004192,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588056916,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:142",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078128,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588283632,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:93",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages_release",
        "mm/page_alloc.c:numa_zonelist_order_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125088,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588848832,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:95",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages_release",
        "mm/hmm.c:hmm_devmem_pages_create",
        "mm/hmm.c:hmm_devmem_pages_create",
        "mm/hmm.c:hmm_devmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237776,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589228018,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:95",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages_release",
        "mm/hmm.c:hmm_devmem_pages_create",
        "mm/hmm.c:hmm_devmem_pages_create",
        "mm/hmm.c:hmm_devmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383744,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589470789,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:95",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467968,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589926283,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:97",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:devm_memremap_pages_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581583488,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590152362,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:97",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648160,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591170862,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:94",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865408,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591666823,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:94",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pageunmap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581910288,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591610848,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:104",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756848,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592784185,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:169",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582038176,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594682917,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:186",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468208,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596419269,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:178",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982544,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596959333,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:177",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194192,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597887051,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:245",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": [
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_block_online",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583379088,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503907168,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:97",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493096976,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286550996,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:97",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286548336,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589754650,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:97",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581616896,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589478874,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:97",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558224,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590198058,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:97",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581608208,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mem_hotplug_done()
```

```json
{
  "name": "mem_hotplug_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590248474,
      "name": "mem_hotplug_done",
      "external": true,
      "loc": "mm/memory_hotplug.c:97",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674400,
      "name": "mem_hotplug_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mem_hotplug_done()
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
void mem_hotplug_done()
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
