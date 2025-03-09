# Function: <code>try_grab_compound_head</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * try_grab_compound_head(struct page * page, int refs, unsigned int flags)
```

```json
{
  "name": "try_grab_compound_head",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581498880,
      "name": "try_grab_compound_head",
      "external": false,
      "loc": "mm/gup.c:81",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071581498880,
      "name": "try_grab_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
struct page * try_grab_compound_head(struct page * page, int refs, unsigned int flags)
```

```json
{
  "name": "try_grab_compound_head",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581538240,
      "name": "try_grab_compound_head",
      "external": false,
      "loc": "mm/gup.c:81",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071581538240,
      "name": "try_grab_compound_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * try_grab_compound_head(struct page * page, int refs, unsigned int flags)
```

```json
{
  "name": "try_grab_compound_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581562112,
      "name": "try_grab_compound_head",
      "external": true,
      "loc": "mm/gup.c:113",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_pte_range",
        "mm/hugetlb.c:follow_hugetlb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562112,
      "name": "try_grab_compound_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * try_grab_compound_head(struct page * page, int refs, unsigned int flags)
```

```json
{
  "name": "try_grab_compound_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581826736,
      "name": "try_grab_compound_head",
      "external": true,
      "loc": "mm/gup.c:127",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_pte_range",
        "mm/hugetlb.c:follow_hugetlb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826736,
      "name": "try_grab_compound_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
struct page * try_grab_compound_head(struct page * page, int refs, unsigned int flags)
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
struct page * try_grab_compound_head(struct page * page, int refs, unsigned int flags)
```
</details>
</li>
</ul>
