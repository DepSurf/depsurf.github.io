# Function: <code>put_compound_head</code>

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
void put_compound_head(struct page * page, int refs, unsigned int flags)
```

```json
{
  "name": "put_compound_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498640,
      "name": "put_compound_head",
      "external": false,
      "loc": "mm/gup.c:2125",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498640,
      "name": "put_compound_head",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void put_compound_head(struct page * page, int refs, unsigned int flags)
```

```json
{
  "name": "put_compound_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581538576,
      "name": "put_compound_head",
      "external": false,
      "loc": "mm/gup.c:126",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:undo_dev_pagemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538576,
      "name": "put_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void put_compound_head(struct page * page, int refs, unsigned int flags)
```

```json
{
  "name": "put_compound_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559856,
      "name": "put_compound_head",
      "external": false,
      "loc": "mm/gup.c:161",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:unpin_user_pages",
        "mm/gup.c:unpin_user_pages",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559856,
      "name": "put_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void put_compound_head(struct page * page, int refs, unsigned int flags)
```

```json
{
  "name": "put_compound_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824480,
      "name": "put_compound_head",
      "external": false,
      "loc": "mm/gup.c:175",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:unpin_user_pages",
        "mm/gup.c:unpin_user_pages",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824480,
      "name": "put_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
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
void put_compound_head(struct page * page, int refs, unsigned int flags)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void put_compound_head(struct page * page, int refs, unsigned int flags)
```
</details>
</li>
</ul>
