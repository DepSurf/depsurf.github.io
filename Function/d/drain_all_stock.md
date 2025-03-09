# Function: <code>drain_all_stock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580924774,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:1951",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581084452,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:1818",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069680,
      "name": "drain_all_stock.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581145312,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:1789",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144704,
      "name": "drain_all_stock.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581192455,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:1800",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191856,
      "name": "drain_all_stock.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581322377,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:1821",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321680,
      "name": "drain_all_stock.part.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
void drain_all_stock(struct mem_cgroup * root_memcg)
```

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581468256,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:1773",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581468256,
      "name": "drain_all_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
void drain_all_stock(struct mem_cgroup * root_memcg)
```

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581553168,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2051",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553168,
      "name": "drain_all_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
void drain_all_stock(struct mem_cgroup * root_memcg)
```

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581667792,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2252",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581667792,
      "name": "drain_all_stock",
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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void drain_all_stock(struct mem_cgroup * root_memcg)
```

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581740080,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2268",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740080,
      "name": "drain_all_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581962307,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2145",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960064,
      "name": "drain_all_stock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582011220,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2368",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008704,
      "name": "drain_all_stock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582039892,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2177",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582037376,
      "name": "drain_all_stock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582347841,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2276",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582345152,
      "name": "drain_all_stock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582842924,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2266",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582840560,
      "name": "drain_all_stock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583388844,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2326",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583386096,
      "name": "drain_all_stock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583609548,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2336",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583606752,
      "name": "drain_all_stock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583804364,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2408",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583801488,
      "name": "drain_all_stock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
void drain_all_stock(struct mem_cgroup * root_memcg)
```

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493192560,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2268",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493192560,
      "name": "drain_all_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
void drain_all_stock(struct mem_cgroup * root_memcg)
```

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226824772,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2268",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226824772,
      "name": "drain_all_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void drain_all_stock(struct mem_cgroup * root_memcg)
```

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286693952,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2268",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286693952,
      "name": "drain_all_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
void drain_all_stock(struct mem_cgroup * root_memcg)
```

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272973126,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2268",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272973126,
      "name": "drain_all_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
void drain_all_stock(struct mem_cgroup * root_memcg)
```

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581708816,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2268",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708816,
      "name": "drain_all_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void drain_all_stock(struct mem_cgroup * root_memcg)
```

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581647744,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2268",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647744,
      "name": "drain_all_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void drain_all_stock(struct mem_cgroup * root_memcg)
```

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581700128,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2268",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581700128,
      "name": "drain_all_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void drain_all_stock(struct mem_cgroup * root_memcg)
```

```json
{
  "name": "drain_all_stock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581767264,
      "name": "drain_all_stock",
      "external": false,
      "loc": "mm/memcontrol.c:2268",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767264,
      "name": "drain_all_stock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void drain_all_stock(struct mem_cgroup * root_memcg)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void drain_all_stock(struct mem_cgroup * root_memcg)
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
