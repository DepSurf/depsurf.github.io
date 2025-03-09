# Function: <code>mem_cgroup_move_account</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page * page, unsigned int nr_pages, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580930672,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:4541",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930672,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581076784,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:4497",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076784,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152384,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:4480",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152384,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581199712,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:4509",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581199712,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581329632,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:4556",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581329632,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581477600,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:4495",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477600,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 931
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559936,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:4781",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559936,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581673968,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5143",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581673968,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581746224,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5477",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581746224,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967104,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5361",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967104,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582016000,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5596",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582016000,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1135
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582041808,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5417",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041808,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349520,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5601",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349520,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1163
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582844464,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5541",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582844464,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1135
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583390992,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5699",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390992,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583616512,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5739",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616512,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1304
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583811392,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5979",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583811392,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1299
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493199368,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5477",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493199368,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
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
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226830792,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5477",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226830792,
      "name": "mem_cgroup_move_account.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286703216,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5477",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286703216,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1000
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
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272978634,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5477",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272978634,
      "name": "mem_cgroup_move_account.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714960,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5477",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714960,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653872,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5477",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653872,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 766
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581706272,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5477",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581706272,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
```

```json
{
  "name": "mem_cgroup_move_account",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581773664,
      "name": "mem_cgroup_move_account",
      "external": false,
      "loc": "mm/memcontrol.c:5477",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773664,
      "name": "mem_cgroup_move_account",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
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
<code>bool compound</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_pages</code>
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
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
int mem_cgroup_move_account(struct page * page, bool compound, struct mem_cgroup * from, struct mem_cgroup * to)
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
