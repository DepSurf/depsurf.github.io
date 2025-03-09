# Function: <code>cancel_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cancel_charge(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580923008,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2164",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923008,
      "name": "cancel_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void cancel_charge(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069312,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2049",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069312,
      "name": "cancel_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void cancel_charge(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144336,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2020",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144336,
      "name": "cancel_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581212770,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2031",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191488,
      "name": "cancel_charge.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581343142,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2058",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319696,
      "name": "cancel_charge.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581490614,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2045",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467856,
      "name": "cancel_charge.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581576470,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2341",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581552768,
      "name": "cancel_charge.part.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581687710,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2542",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581667280,
      "name": "cancel_charge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581761166,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2714",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739568,
      "name": "cancel_charge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581965466,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2644",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958064,
      "name": "cancel_charge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582011914,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2907",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc"
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
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582034666,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2702",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:obj_cgroup_charge_pages"
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
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582331418,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2770",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:obj_cgroup_charge_pages"
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
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582833978,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2760",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc"
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
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583378970,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2830",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc"
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
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583599210,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2840",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc"
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493215148,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2714",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493191680,
      "name": "cancel_charge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226846192,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2714",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226824048,
      "name": "cancel_charge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286727516,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2714",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286692512,
      "name": "cancel_charge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272991558,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2714",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272972404,
      "name": "cancel_charge.part.0",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581729902,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2714",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708304,
      "name": "cancel_charge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581668670,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2714",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647248,
      "name": "cancel_charge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581721214,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2714",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699616,
      "name": "cancel_charge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581789294,
      "name": "cancel_charge",
      "external": false,
      "loc": "mm/memcontrol.c:2714",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581766704,
      "name": "cancel_charge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void cancel_charge(struct mem_cgroup * memcg, unsigned int nr_pages)
```
</details>
</li>
</ul>
