# Function: <code>__section_nr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580825488,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:108",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_remove_one_section",
        "mm/memory_hotplug.c:__remove_pages",
        "drivers/base/memory.c:init_memory_block",
        "drivers/base/memory.c:find_memory_block_hinted",
        "drivers/base/memory.c:unregister_memory_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825488,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950976,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:104",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_remove_one_section",
        "mm/memory_hotplug.c:__remove_pages",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/base/memory.c:is_zone_device_section",
        "drivers/base/memory.c:init_memory_block",
        "drivers/base/memory.c:find_memory_block_hinted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950976,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581024256,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:104",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_remove_one_section",
        "mm/memory_hotplug.c:__remove_pages",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/base/memory.c:is_zone_device_section",
        "drivers/base/memory.c:init_memory_block",
        "drivers/base/memory.c:find_memory_block_hinted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024256,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581070477,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:104",
      "file": "mm/sparse.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_remove_one_section",
        "mm/sparse.c:section_mark_present"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:__remove_pages",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/base/memory.c:init_memory_block",
        "drivers/base/memory.c:find_memory_block_hinted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070032,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581181168,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:100",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_remove_one_section",
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:memory_present",
        "mm/memory_hotplug.c:__remove_pages",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/base/memory.c:init_memory_block",
        "drivers/base/memory.c:find_memory_block_hinted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181168,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326000,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:100",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_remove_one_section",
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:memory_present",
        "mm/memory_hotplug.c:__remove_pages",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/base/memory.c:init_memory_block",
        "drivers/base/memory.c:find_memory_block_hinted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326000,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581410112,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:101",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_remove_one_section",
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:memory_present",
        "mm/memory_hotplug.c:__remove_pages",
        "drivers/base/memory.c:unregister_memory_section",
        "drivers/base/memory.c:init_memory_block",
        "drivers/base/memory.c:find_memory_block_hinted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410112,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
long unsigned int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522288,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:112",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:memory_present",
        "drivers/base/memory.c:find_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522288,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
long unsigned int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581587552,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:114",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:memory_present",
        "drivers/base/memory.c:find_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587552,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
long unsigned int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581799648,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:113",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:section_mark_present",
        "drivers/base/memory.c:find_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799648,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long unsigned int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581847552,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:112",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:section_mark_present",
        "drivers/base/memory.c:find_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847552,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long unsigned int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581878352,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:112",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:section_mark_present",
        "drivers/base/memory.c:find_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878352,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long unsigned int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493025696,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:114",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:memory_present",
        "drivers/base/memory.c:find_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493025696,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
long unsigned int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286454912,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:114",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:memory_present",
        "drivers/base/memory.c:find_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286454912,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
long unsigned int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272901042,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:114",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:memory_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272901042,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
long unsigned int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581556288,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:114",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:memory_present",
        "drivers/base/memory.c:find_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556288,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
long unsigned int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581497936,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:114",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:memory_present",
        "drivers/base/memory.c:find_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581497936,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
long unsigned int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581547600,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:114",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:memory_present",
        "drivers/base/memory.c:find_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581547600,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
long unsigned int __section_nr(struct mem_section * ms)
```

```json
{
  "name": "__section_nr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612720,
      "name": "__section_nr",
      "external": true,
      "loc": "mm/sparse.c:114",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:memory_present",
        "drivers/base/memory.c:find_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612720,
      "name": "__section_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
long unsigned int __section_nr(struct mem_section * ms)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int __section_nr(struct mem_section * ms)
```
</details>
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
