# Function: <code>apply_to_p4d_range</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580903631,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2124",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581003021,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2241",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581141810,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2283",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581216450,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2019",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581289794,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2073",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581348530,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2078",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int apply_to_p4d_range(struct mm_struct * mm, pgd_t * pgd, long unsigned int addr, long unsigned int end, pte_fn_t fn, void * data, bool create, pgtbl_mod_mask * mask)
```

```json
{
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581545024,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2303",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__apply_to_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545024,
      "name": "apply_to_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1143
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581588442,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2482",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581611657,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2527",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581878614,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2622",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582278230,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2715",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582770702,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2686",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582986855,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2686",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583162199,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2709",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492756248,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2078",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226567240,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2078",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286118120,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2078",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272737882,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2078",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581317378,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2078",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581261500,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2078",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581308578,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2078",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
  "name": "apply_to_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581372578,
      "name": "apply_to_p4d_range",
      "external": false,
      "loc": "mm/memory.c:2078",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int apply_to_p4d_range(struct mm_struct * mm, pgd_t * pgd, long unsigned int addr, long unsigned int end, pte_fn_t fn, void * data, bool create, pgtbl_mod_mask * mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int apply_to_p4d_range(struct mm_struct * mm, pgd_t * pgd, long unsigned int addr, long unsigned int end, pte_fn_t fn, void * data, bool create, pgtbl_mod_mask * mask)
```
</details>
</li>
</ul>
