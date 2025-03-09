# Function: <code>map_pte</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580905356,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:26",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580950148,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:26",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581051416,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581189929,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581272877,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581347341,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581406653,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
bool map_pte(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581603664,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581603664,
      "name": "map_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
bool map_pte(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650960,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650960,
      "name": "map_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581673620,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581942969,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582352521,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582853830,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool map_pte(struct page_vma_mapped_walk * pvmw, spinlock_t * * ptlp)
```

```json
{
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583068672,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068672,
      "name": "map_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
bool map_pte(struct page_vma_mapped_walk * pvmw, spinlock_t * * ptlp)
```

```json
{
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583250544,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583250544,
      "name": "map_pte",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492806848,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226619168,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286184836,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272770834,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581375501,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581318789,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581366701,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
  "name": "map_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581430595,
      "name": "map_pte",
      "external": false,
      "loc": "mm/page_vma_mapped.c:16",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
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
bool map_pte(struct page_vma_mapped_walk * pvmw)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool map_pte(struct page_vma_mapped_walk * pvmw)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
bool map_pte(struct page_vma_mapped_walk * pvmw, spinlock_t * * ptlp)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
