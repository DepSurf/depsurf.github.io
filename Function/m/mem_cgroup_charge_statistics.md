# Function: <code>mem_cgroup_charge_statistics</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580919664,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:697",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919664,
      "name": "mem_cgroup_charge_statistics.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062336,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:593",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062336,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581137456,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:596",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137456,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581184752,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:566",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184752,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581313920,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:580",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581313920,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581466944,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:551",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581466944,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581551536,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:689",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551536,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581673744,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:834",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581673744,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581746000,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:845",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581746000,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581956896,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:835",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956896,
      "name": "mem_cgroup_charge_statistics.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582003472,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:938",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003472,
      "name": "mem_cgroup_charge_statistics.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582029280,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:816",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029280,
      "name": "mem_cgroup_charge_statistics.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582349376,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:856",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349376,
      "name": "mem_cgroup_charge_statistics.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582844304,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:836",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582844304,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583412307,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:916",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
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
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583632552,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:941",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
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
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583827477,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:984",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_replace_folio",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493199112,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:845",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493199112,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226830552,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:845",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226830552,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286702816,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:845",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286702816,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272978380,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:845",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272978380,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714736,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:845",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714736,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653648,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:845",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653648,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581706048,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:845",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581706048,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_statistics",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581773440,
      "name": "mem_cgroup_charge_statistics",
      "external": false,
      "loc": "mm/memcontrol.c:845",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773440,
      "name": "mem_cgroup_charge_statistics",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```
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
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, struct page * page, bool compound, int nr_pages)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, int nr_pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void mem_cgroup_charge_statistics(struct mem_cgroup * memcg, int nr_pages)
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
