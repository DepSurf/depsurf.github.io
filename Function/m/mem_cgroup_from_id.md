# Function: <code>mem_cgroup_from_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580942805,
      "name": "mem_cgroup_from_id",
      "external": false,
      "loc": "mm/memcontrol.c:283",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581091404,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:4125",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089312,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581166620,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:4100",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164304,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581214435,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:4120",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581212192,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581345059,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:4147",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342544,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581492882,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:4081",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581489840,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581578754,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:4354",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575616,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581689925,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:4694",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686880,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581763349,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5014",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581760336,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581982682,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:4896",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581980128,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582033002,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5158",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030368,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582059786,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:4926",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056560,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582367706,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5093",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582364608,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582865713,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5057",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582862064,
      "name": "mem_cgroup_from_id",
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583413137,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5178",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio"
      ],
      "caller_func": [
        "mm/vmscan.c:run_cmd",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583409488,
      "name": "mem_cgroup_from_id",
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583633409,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5205",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio"
      ],
      "caller_func": [
        "mm/vmscan.c:run_cmd",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:lru_gen_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629744,
      "name": "mem_cgroup_from_id",
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583828335,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5402",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio"
      ],
      "caller_func": [
        "mm/vmscan.c:run_cmd",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:lru_gen_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824320,
      "name": "mem_cgroup_from_id",
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493217288,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5014",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493214216,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226848552,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5014",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226845200,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286731000,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5014",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286725968,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272993500,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5014",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272990724,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581732085,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5014",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729072,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581670757,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5014",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581667840,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581723397,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5014",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581720384,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
```

```json
{
  "name": "mem_cgroup_from_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581791613,
      "name": "mem_cgroup_from_id",
      "external": true,
      "loc": "mm/memcontrol.c:5014",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": [
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788384,
      "name": "mem_cgroup_from_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct mem_cgroup * mem_cgroup_from_id(short unsigned int id)
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
