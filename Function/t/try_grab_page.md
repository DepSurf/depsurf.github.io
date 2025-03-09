# Function: <code>try_grab_page</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool try_grab_page(struct page * page, unsigned int flags)
```

```json
{
  "name": "try_grab_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581497552,
      "name": "try_grab_page",
      "external": true,
      "loc": "mm/gup.c:147",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581497552,
      "name": "try_grab_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071581499952,
      "name": "try_grab_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool try_grab_page(struct page * page, unsigned int flags)
```

```json
{
  "name": "try_grab_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581538064,
      "name": "try_grab_page",
      "external": true,
      "loc": "mm/gup.c:169",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538064,
      "name": "try_grab_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071581540112,
      "name": "try_grab_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
bool try_grab_page(struct page * page, unsigned int flags)
```

```json
{
  "name": "try_grab_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581563440,
      "name": "try_grab_page",
      "external": true,
      "loc": "mm/gup.c:197",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563440,
      "name": "try_grab_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
bool try_grab_page(struct page * page, unsigned int flags)
```

```json
{
  "name": "try_grab_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581828208,
      "name": "try_grab_page",
      "external": true,
      "loc": "mm/gup.c:209",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828208,
      "name": "try_grab_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
bool try_grab_page(struct page * page, unsigned int flags)
```

```json
{
  "name": "try_grab_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582221312,
      "name": "try_grab_page",
      "external": true,
      "loc": "mm/gup.c:202",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221312,
      "name": "try_grab_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int try_grab_page(struct page * page, unsigned int flags)
```

```json
{
  "name": "try_grab_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582710768,
      "name": "try_grab_page",
      "external": true,
      "loc": "mm/gup.c:214",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582710768,
      "name": "try_grab_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int try_grab_page(struct page * page, unsigned int flags)
```

```json
{
  "name": "try_grab_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582925568,
      "name": "try_grab_page",
      "external": true,
      "loc": "mm/gup.c:225",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582925568,
      "name": "try_grab_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int try_grab_page(struct page * page, unsigned int flags)
```

```json
{
  "name": "try_grab_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583099680,
      "name": "try_grab_page",
      "external": true,
      "loc": "mm/gup.c:225",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583099680,
      "name": "try_grab_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
bool try_grab_page(struct page * page, unsigned int flags)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
