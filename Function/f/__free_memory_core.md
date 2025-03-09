# Function: <code>__free_memory_core</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int __free_memory_core(phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595141864,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/nobootmem.c:110",
      "file": "mm/nobootmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/nobootmem.c:free_all_bootmem",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/nobootmem.c:free_all_bootmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595141864,
      "name": "__free_memory_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 145
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
long unsigned int __free_memory_core(phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595312942,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/nobootmem.c:111",
      "file": "mm/nobootmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/nobootmem.c:free_all_bootmem",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/nobootmem.c:free_all_bootmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595312942,
      "name": "__free_memory_core",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 145
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
long unsigned int __free_memory_core(phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595561249,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/nobootmem.c:114",
      "file": "mm/nobootmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/nobootmem.c:free_all_bootmem",
        "mm/nobootmem.c:free_all_bootmem",
        "mm/nobootmem.c:free_all_bootmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595561249,
      "name": "__free_memory_core",
      "section": ".init.text",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596488821,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/nobootmem.c:114",
      "file": "mm/nobootmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/nobootmem.c:free_all_bootmem"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602815637,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/nobootmem.c:115",
      "file": "mm/nobootmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/nobootmem.c:free_all_bootmem"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602988883,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/nobootmem.c:115",
      "file": "mm/nobootmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/nobootmem.c:free_all_bootmem"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604790714,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1907",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604893575,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1908",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604927480,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1908",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609239817,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1960",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:free_low_memory_core_early"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612306226,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1990",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:free_low_memory_core_early"
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
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614448277,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1991",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615391334,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:2019",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617181564,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:2026",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627873987,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:2044",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619635213,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:2075",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:free_low_memory_core_early"
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
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621942470,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:2134",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510967172,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1908",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243453656,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1908",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302620812,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1908",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270693194,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1908",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604832940,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1908",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604802001,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1908",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604910124,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1908",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__free_memory_core",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604931661,
      "name": "__free_memory_core",
      "external": false,
      "loc": "mm/memblock.c:1908",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all"
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
long unsigned int __free_memory_core(phys_addr_t start, phys_addr_t end)
```
</details>
</li>
</ul>
