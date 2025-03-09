# Function: <code>split_page_memcg</code>

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
void split_page_memcg(struct page * head, unsigned int nr)
```

```json
{
  "name": "split_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028592,
      "name": "split_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3302",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:make_alloc_exact",
        "mm/huge_memory.c:__split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028592,
      "name": "split_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void split_page_memcg(struct page * head, unsigned int nr)
```

```json
{
  "name": "split_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054624,
      "name": "split_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3134",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:make_alloc_exact",
        "mm/huge_memory.c:__split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054624,
      "name": "split_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void split_page_memcg(struct page * head, unsigned int nr)
```

```json
{
  "name": "split_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582362480,
      "name": "split_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3302",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:split_page",
        "mm/huge_memory.c:__split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582362480,
      "name": "split_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void split_page_memcg(struct page * head, unsigned int nr)
```

```json
{
  "name": "split_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582859712,
      "name": "split_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3306",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:split_page",
        "mm/huge_memory.c:__split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582859712,
      "name": "split_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void split_page_memcg(struct page * head, unsigned int nr)
```

```json
{
  "name": "split_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407008,
      "name": "split_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3406",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:make_alloc_exact",
        "mm/page_alloc.c:make_alloc_exact",
        "mm/page_alloc.c:split_page",
        "mm/huge_memory.c:__split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407008,
      "name": "split_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void split_page_memcg(struct page * head, unsigned int nr)
```

```json
{
  "name": "split_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583627312,
      "name": "split_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3417",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:make_alloc_exact",
        "mm/page_alloc.c:make_alloc_exact",
        "mm/page_alloc.c:split_page",
        "mm/huge_memory.c:__split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583627312,
      "name": "split_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void split_page_memcg(struct page * head, unsigned int nr)
```

```json
{
  "name": "split_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583821936,
      "name": "split_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3609",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:make_alloc_exact",
        "mm/page_alloc.c:make_alloc_exact",
        "mm/page_alloc.c:split_page",
        "mm/huge_memory.c:__split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583821936,
      "name": "split_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void split_page_memcg(struct page * head, unsigned int nr)
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
