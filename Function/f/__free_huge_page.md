# Function: <code>__free_huge_page</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __free_huge_page(struct page * page)
```

```json
{
  "name": "__free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543616,
      "name": "__free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1259",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:free_hpage_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543616,
      "name": "__free_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void __free_huge_page(struct page * page)
```

```json
{
  "name": "__free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581753312,
      "name": "__free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1398",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_hpage_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753312,
      "name": "__free_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
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
void __free_huge_page(struct page * page)
```

```json
{
  "name": "__free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801408,
      "name": "__free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1425",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_hpage_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801408,
      "name": "__free_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
void __free_huge_page(struct page * page)
```

```json
{
  "name": "__free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492975920,
      "name": "__free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1259",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:free_hpage_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492975920,
      "name": "__free_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __free_huge_page(struct page * page)
```

```json
{
  "name": "__free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286396048,
      "name": "__free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1259",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:free_hpage_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286396048,
      "name": "__free_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
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
void __free_huge_page(struct page * page)
```

```json
{
  "name": "__free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272882274,
      "name": "__free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1259",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:free_hpage_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272882274,
      "name": "__free_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
void __free_huge_page(struct page * page)
```

```json
{
  "name": "__free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581512352,
      "name": "__free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1259",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:free_hpage_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581512352,
      "name": "__free_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void __free_huge_page(struct page * page)
```

```json
{
  "name": "__free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581454544,
      "name": "__free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1259",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:free_hpage_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454544,
      "name": "__free_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void __free_huge_page(struct page * page)
```

```json
{
  "name": "__free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581503664,
      "name": "__free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1259",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:free_hpage_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503664,
      "name": "__free_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void __free_huge_page(struct page * page)
```

```json
{
  "name": "__free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581568656,
      "name": "__free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1259",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:free_hpage_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568656,
      "name": "__free_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void __free_huge_page(struct page * page)
```
</details>
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
void __free_huge_page(struct page * page)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __free_huge_page(struct page * page)
```
</details>
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
