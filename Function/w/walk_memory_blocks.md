# Function: <code>walk_memory_blocks</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586157056,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:860",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/node.c:link_mem_sections"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586157056,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586305408,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:834",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/node.c:link_mem_sections"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586305408,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587075104,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:774",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_remove_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/node.c:link_mem_sections"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075104,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587159488,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:765",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_remove_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/node.c:link_mem_sections"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587159488,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587047184,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:834",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/node.c:link_mem_sections"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587047184,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587616864,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:856",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/node.c:link_mem_sections"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587616864,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588957392,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:952",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/node.c:node_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588957392,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590473152,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:959",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/node.c:node_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590473152,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590796080,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:954",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/node.c:node_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590796080,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591139760,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:1007",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/node.c:node_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591139760,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499139128,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:834",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/node.c:link_mem_sections"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499139128,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292331616,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:834",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime",
        "arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime",
        "arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime",
        "arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/base/node.c:link_mem_sections"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292331616,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586068656,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:834",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/node.c:link_mem_sections"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068656,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585914608,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:834",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/base/node.c:link_mem_sections"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585914608,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586253376,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:834",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/node.c:link_mem_sections"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586253376,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```

```json
{
  "name": "walk_memory_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586364320,
      "name": "walk_memory_blocks",
      "external": true,
      "loc": "drivers/base/memory.c:834",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/node.c:link_mem_sections"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586364320,
      "name": "walk_memory_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
```
</details>
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void * arg, walk_memory_blocks_func_t func)
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
