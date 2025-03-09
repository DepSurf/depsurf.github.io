# Function: <code>__kernel_poison_pages</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __kernel_poison_pages(struct page * page, int n)
```

```json
{
  "name": "__kernel_poison_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871296,
      "name": "__kernel_poison_pages",
      "external": true,
      "loc": "mm/page_poison.c:33",
      "file": "mm/page_poison.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:clear_or_poison_free_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871296,
      "name": "__kernel_poison_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void __kernel_poison_pages(struct page * page, int n)
```

```json
{
  "name": "__kernel_poison_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901792,
      "name": "__kernel_poison_pages",
      "external": true,
      "loc": "mm/page_poison.c:34",
      "file": "mm/page_poison.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901792,
      "name": "__kernel_poison_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void __kernel_poison_pages(struct page * page, int n)
```

```json
{
  "name": "__kernel_poison_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196480,
      "name": "__kernel_poison_pages",
      "external": true,
      "loc": "mm/page_poison.c:34",
      "file": "mm/page_poison.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196480,
      "name": "__kernel_poison_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void __kernel_poison_pages(struct page * page, int n)
```

```json
{
  "name": "__kernel_poison_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660336,
      "name": "__kernel_poison_pages",
      "external": true,
      "loc": "mm/page_poison.c:34",
      "file": "mm/page_poison.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660336,
      "name": "__kernel_poison_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void __kernel_poison_pages(struct page * page, int n)
```

```json
{
  "name": "__kernel_poison_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583183984,
      "name": "__kernel_poison_pages",
      "external": true,
      "loc": "mm/page_poison.c:34",
      "file": "mm/page_poison.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583183984,
      "name": "__kernel_poison_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void __kernel_poison_pages(struct page * page, int n)
```

```json
{
  "name": "__kernel_poison_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583401744,
      "name": "__kernel_poison_pages",
      "external": true,
      "loc": "mm/page_poison.c:34",
      "file": "mm/page_poison.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:__free_pages_ok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583401744,
      "name": "__kernel_poison_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void __kernel_poison_pages(struct page * page, int n)
```

```json
{
  "name": "__kernel_poison_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583641200,
      "name": "__kernel_poison_pages",
      "external": true,
      "loc": "mm/page_poison.c:33",
      "file": "mm/page_poison.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:__free_pages_ok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641200,
      "name": "__kernel_poison_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __kernel_poison_pages(struct page * page, int n)
```
</details>
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
