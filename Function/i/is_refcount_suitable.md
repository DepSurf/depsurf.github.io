# Function: <code>is_refcount_suitable</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool is_refcount_suitable(struct page * page)
```

```json
{
  "name": "is_refcount_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924672,
      "name": "is_refcount_suitable",
      "external": false,
      "loc": "mm/khugepaged.c:573",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924672,
      "name": "is_refcount_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
bool is_refcount_suitable(struct page * page)
```

```json
{
  "name": "is_refcount_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581971744,
      "name": "is_refcount_suitable",
      "external": false,
      "loc": "mm/khugepaged.c:588",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971744,
      "name": "is_refcount_suitable",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool is_refcount_suitable(struct page * page)
```

```json
{
  "name": "is_refcount_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581999856,
      "name": "is_refcount_suitable",
      "external": false,
      "loc": "mm/khugepaged.c:586",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999856,
      "name": "is_refcount_suitable",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool is_refcount_suitable(struct page * page)
```

```json
{
  "name": "is_refcount_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302304,
      "name": "is_refcount_suitable",
      "external": false,
      "loc": "mm/khugepaged.c:590",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302304,
      "name": "is_refcount_suitable",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool is_refcount_suitable(struct page * page)
```

```json
{
  "name": "is_refcount_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582794016,
      "name": "is_refcount_suitable",
      "external": false,
      "loc": "mm/khugepaged.c:581",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582794016,
      "name": "is_refcount_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
bool is_refcount_suitable(struct page * page)
```

```json
{
  "name": "is_refcount_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583334464,
      "name": "is_refcount_suitable",
      "external": false,
      "loc": "mm/khugepaged.c:522",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583334464,
      "name": "is_refcount_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
bool is_refcount_suitable(struct page * page)
```

```json
{
  "name": "is_refcount_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583554080,
      "name": "is_refcount_suitable",
      "external": false,
      "loc": "mm/khugepaged.c:534",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583554080,
      "name": "is_refcount_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
bool is_refcount_suitable(struct folio * folio)
```

```json
{
  "name": "is_refcount_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583737712,
      "name": "is_refcount_suitable",
      "external": false,
      "loc": "mm/khugepaged.c:524",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737712,
      "name": "is_refcount_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool is_refcount_suitable(struct page * page)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
</details>
</li>
</ul>
