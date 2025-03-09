# Function: <code>find_next_iomem_res</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int find_next_iomem_res(struct resource * res, char * name, bool first_level_children_only)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395600,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:342",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_iomem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_system_ram_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395600,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int find_next_iomem_res(struct resource * res, long unsigned int desc, bool first_level_children_only)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579407968,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:361",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407968,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int find_next_iomem_res(struct resource * res, long unsigned int desc, bool first_level_children_only)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579428272,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:361",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579428272,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int find_next_iomem_res(struct resource * res, long unsigned int desc, bool first_level_children_only)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416000,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:361",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416000,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int find_next_iomem_res(struct resource * res, long unsigned int desc, bool first_level_children_only)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579443872,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:361",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443872,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
int find_next_iomem_res(struct resource * res, long unsigned int desc, bool first_level_children_only)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579458544,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:328",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458544,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579492096,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:340",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492096,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509824,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:341",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509824,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535888,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:341",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535888,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568672,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:341",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:page_is_ram",
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568672,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550032,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:343",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:page_is_ram",
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550032,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579553840,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:338",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:page_is_ram",
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553840,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626400,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:338",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:page_is_ram",
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626400,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720032,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:325",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:page_is_ram",
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720032,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579847008,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:325",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:page_is_ram",
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579847008,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897232,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:325",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:page_is_ram",
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897232,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934528,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:325",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:page_is_ram",
        "kernel/resource.c:walk_mem_res",
        "kernel/resource.c:walk_system_ram_res_rev",
        "kernel/resource.c:walk_system_ram_res",
        "kernel/resource.c:walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934528,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490682048,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:341",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490682048,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224753320,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:341",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224753320,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283504912,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:341",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283504912,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271416208,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:341",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271416208,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509552,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:341",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509552,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438352,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:341",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438352,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509472,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:341",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509472,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int find_next_iomem_res(resource_size_t start, resource_size_t end, long unsigned int flags, long unsigned int desc, bool first_lvl, struct resource * res)
```

```json
{
  "name": "find_next_iomem_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542336,
      "name": "find_next_iomem_res",
      "external": false,
      "loc": "kernel/resource.c:341",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:walk_system_ram_range",
        "kernel/resource.c:__walk_iomem_res_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542336,
      "name": "find_next_iomem_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int desc</code>
</li>
<li>
<b>Param removed. </b>
<code>char * name</code>
</li>
</ul>
</details>
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
<code>bool first_level_children_only</code>
</li>
<li>
<b>Param reordered. </b>
<code>res, desc, first_level_children_only</code> ➡️ <code>start, end, flags, desc, first_lvl, res</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool first_lvl</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, end, flags, desc, first_lvl, res</code> ➡️ <code>start, end, flags, desc, res</code>
</li>
</ul>
</details>
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
