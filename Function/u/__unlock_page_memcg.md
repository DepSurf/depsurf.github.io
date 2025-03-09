# Function: <code>__unlock_page_memcg</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581188313,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1672",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:unlock_page_memcg"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581209568,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581317417,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1686",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:unlock_page_memcg"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339936,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581463625,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1643",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:unlock_page_memcg"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487424,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581547833,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1921",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:unlock_page_memcg",
        "mm/memcontrol.c:unlock_page_memcg"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572944,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684240,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2122",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memcontrol.c:unlock_page_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684240,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756672,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2138",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memcontrol.c:unlock_page_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756672,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581967450,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2013",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:unlock_page_memcg"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975840,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582016384,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2208",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:unlock_page_memcg"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025552,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582042187,
      "name": "__unlock_page_memcg",
      "external": false,
      "loc": "mm/memcontrol.c:2017",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:unlock_page_memcg"
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
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582349899,
      "name": "__unlock_page_memcg",
      "external": false,
      "loc": "mm/memcontrol.c:2069",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:unlock_page_memcg"
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493210304,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2138",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memcontrol.c:unlock_page_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493210304,
      "name": "__unlock_page_memcg",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226840616,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2138",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memcontrol.c:unlock_page_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226840616,
      "name": "__unlock_page_memcg",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286719872,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2138",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memcontrol.c:unlock_page_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286719872,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272986984,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2138",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memcontrol.c:unlock_page_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272986984,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725408,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2138",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memcontrol.c:unlock_page_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725408,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664208,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2138",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memcontrol.c:unlock_page_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664208,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716720,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2138",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memcontrol.c:unlock_page_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716720,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __unlock_page_memcg(struct mem_cgroup * memcg)
```

```json
{
  "name": "__unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784368,
      "name": "__unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2138",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memcontrol.c:unlock_page_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784368,
      "name": "__unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void __unlock_page_memcg(struct mem_cgroup * memcg)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void __unlock_page_memcg(struct mem_cgroup * memcg)
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
