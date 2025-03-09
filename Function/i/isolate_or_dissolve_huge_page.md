# Function: <code>isolate_or_dissolve_huge_page</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int isolate_or_dissolve_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_or_dissolve_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852592,
      "name": "isolate_or_dissolve_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2426",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852592,
      "name": "isolate_or_dissolve_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int isolate_or_dissolve_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_or_dissolve_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "isolate_or_dissolve_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2705",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592215567,
      "name": "isolate_or_dissolve_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071582144032,
      "name": "isolate_or_dissolve_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int isolate_or_dissolve_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_or_dissolve_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "isolate_or_dissolve_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2816",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593994254,
      "name": "isolate_or_dissolve_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071582597296,
      "name": "isolate_or_dissolve_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 870
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int isolate_or_dissolve_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_or_dissolve_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "isolate_or_dissolve_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2979",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596044282,
      "name": "isolate_or_dissolve_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071583116368,
      "name": "isolate_or_dissolve_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int isolate_or_dissolve_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_or_dissolve_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "isolate_or_dissolve_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:3011",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596566710,
      "name": "isolate_or_dissolve_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071583326880,
      "name": "isolate_or_dissolve_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int isolate_or_dissolve_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_or_dissolve_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "isolate_or_dissolve_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:3110",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597472235,
      "name": "isolate_or_dissolve_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583563056,
      "name": "isolate_or_dissolve_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int isolate_or_dissolve_huge_page(struct page * page, struct list_head * list)
```
</details>
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
