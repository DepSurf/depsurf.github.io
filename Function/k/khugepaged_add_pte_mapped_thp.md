# Function: <code>khugepaged_add_pte_mapped_thp</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581715368,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1268",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
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
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581930133,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1386",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables"
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
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581976606,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1413",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables"
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
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582004619,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1403",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables"
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
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582307061,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1407",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables"
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
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582793026,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1385",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool khugepaged_add_pte_mapped_thp(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583321056,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1343",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:retract_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583321056,
      "name": "khugepaged_add_pte_mapped_thp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
bool khugepaged_add_pte_mapped_thp(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583539728,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1466",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:retract_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583539728,
      "name": "khugepaged_add_pte_mapped_thp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    }
  ]
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
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493162064,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1268",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286658568,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1268",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581684104,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1268",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
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
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581622698,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1268",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
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
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581675416,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1268",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
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
  "name": "khugepaged_add_pte_mapped_thp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581742044,
      "name": "khugepaged_add_pte_mapped_thp",
      "external": false,
      "loc": "mm/khugepaged.c:1268",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool khugepaged_add_pte_mapped_thp(struct mm_struct * mm, long unsigned int addr)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool khugepaged_add_pte_mapped_thp(struct mm_struct * mm, long unsigned int addr)
```
</details>
</li>
</ul>
