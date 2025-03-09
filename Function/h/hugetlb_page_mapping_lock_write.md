# Function: <code>hugetlb_page_mapping_lock_write</code>

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
struct address_space * hugetlb_page_mapping_lock_write(struct page * hpage)
```

```json
{
  "name": "hugetlb_page_mapping_lock_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581755408,
      "name": "hugetlb_page_mapping_lock_write",
      "external": true,
      "loc": "mm/hugetlb.c:1637",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755408,
      "name": "hugetlb_page_mapping_lock_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
struct address_space * hugetlb_page_mapping_lock_write(struct page * hpage)
```

```json
{
  "name": "hugetlb_page_mapping_lock_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581803536,
      "name": "hugetlb_page_mapping_lock_write",
      "external": true,
      "loc": "mm/hugetlb.c:1618",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803536,
      "name": "hugetlb_page_mapping_lock_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct address_space * hugetlb_page_mapping_lock_write(struct page * hpage)
```

```json
{
  "name": "hugetlb_page_mapping_lock_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830848,
      "name": "hugetlb_page_mapping_lock_write",
      "external": true,
      "loc": "mm/hugetlb.c:1576",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830848,
      "name": "hugetlb_page_mapping_lock_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct address_space * hugetlb_page_mapping_lock_write(struct page * hpage)
```

```json
{
  "name": "hugetlb_page_mapping_lock_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582120128,
      "name": "hugetlb_page_mapping_lock_write",
      "external": true,
      "loc": "mm/hugetlb.c:1767",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120128,
      "name": "hugetlb_page_mapping_lock_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct address_space * hugetlb_page_mapping_lock_write(struct page * hpage)
```

```json
{
  "name": "hugetlb_page_mapping_lock_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582565152,
      "name": "hugetlb_page_mapping_lock_write",
      "external": true,
      "loc": "mm/hugetlb.c:1879",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582565152,
      "name": "hugetlb_page_mapping_lock_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct address_space * hugetlb_page_mapping_lock_write(struct page * hpage)
```

```json
{
  "name": "hugetlb_page_mapping_lock_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583084000,
      "name": "hugetlb_page_mapping_lock_write",
      "external": true,
      "loc": "mm/hugetlb.c:2075",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583084000,
      "name": "hugetlb_page_mapping_lock_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct address_space * hugetlb_page_mapping_lock_write(struct page * hpage)
```

```json
{
  "name": "hugetlb_page_mapping_lock_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583294608,
      "name": "hugetlb_page_mapping_lock_write",
      "external": true,
      "loc": "mm/hugetlb.c:2102",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583294608,
      "name": "hugetlb_page_mapping_lock_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct address_space * hugetlb_page_mapping_lock_write(struct page * hpage)
```

```json
{
  "name": "hugetlb_page_mapping_lock_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583531296,
      "name": "hugetlb_page_mapping_lock_write",
      "external": true,
      "loc": "mm/hugetlb.c:2184",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583531296,
      "name": "hugetlb_page_mapping_lock_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct address_space * hugetlb_page_mapping_lock_write(struct page * hpage)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
