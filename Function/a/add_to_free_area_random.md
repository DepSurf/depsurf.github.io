# Function: <code>add_to_free_area_random</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void add_to_free_area_random(struct page * page, struct free_area * area, int migratetype)
```

```json
{
  "name": "add_to_free_area_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581418672,
      "name": "add_to_free_area_random",
      "external": true,
      "loc": "mm/shuffle.c:186",
      "file": "mm/shuffle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418672,
      "name": "add_to_free_area_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void add_to_free_area_random(struct page * page, struct free_area * area, int migratetype)
```

```json
{
  "name": "add_to_free_area_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581479616,
      "name": "add_to_free_area_random",
      "external": true,
      "loc": "mm/shuffle.c:186",
      "file": "mm/shuffle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479616,
      "name": "add_to_free_area_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
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
void add_to_free_area_random(struct page * page, struct free_area * area, int migratetype)
```

```json
{
  "name": "add_to_free_area_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492888568,
      "name": "add_to_free_area_random",
      "external": true,
      "loc": "mm/shuffle.c:186",
      "file": "mm/shuffle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492888568,
      "name": "add_to_free_area_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void add_to_free_area_random(struct page * page, struct free_area * area, int migratetype)
```

```json
{
  "name": "add_to_free_area_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226686120,
      "name": "add_to_free_area_random",
      "external": true,
      "loc": "mm/shuffle.c:186",
      "file": "mm/shuffle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226686120,
      "name": "add_to_free_area_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void add_to_free_area_random(struct page * page, struct free_area * area, int migratetype)
```

```json
{
  "name": "add_to_free_area_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286287056,
      "name": "add_to_free_area_random",
      "external": true,
      "loc": "mm/shuffle.c:186",
      "file": "mm/shuffle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286287056,
      "name": "add_to_free_area_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void add_to_free_area_random(struct page * page, struct free_area * area, int migratetype)
```

```json
{
  "name": "add_to_free_area_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272827214,
      "name": "add_to_free_area_random",
      "external": true,
      "loc": "mm/shuffle.c:186",
      "file": "mm/shuffle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272827214,
      "name": "add_to_free_area_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void add_to_free_area_random(struct page * page, struct free_area * area, int migratetype)
```

```json
{
  "name": "add_to_free_area_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581448464,
      "name": "add_to_free_area_random",
      "external": true,
      "loc": "mm/shuffle.c:186",
      "file": "mm/shuffle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448464,
      "name": "add_to_free_area_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void add_to_free_area_random(struct page * page, struct free_area * area, int migratetype)
```

```json
{
  "name": "add_to_free_area_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581390832,
      "name": "add_to_free_area_random",
      "external": true,
      "loc": "mm/shuffle.c:186",
      "file": "mm/shuffle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390832,
      "name": "add_to_free_area_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void add_to_free_area_random(struct page * page, struct free_area * area, int migratetype)
```

```json
{
  "name": "add_to_free_area_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581439664,
      "name": "add_to_free_area_random",
      "external": true,
      "loc": "mm/shuffle.c:186",
      "file": "mm/shuffle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439664,
      "name": "add_to_free_area_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void add_to_free_area_random(struct page * page, struct free_area * area, int migratetype)
```

```json
{
  "name": "add_to_free_area_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504160,
      "name": "add_to_free_area_random",
      "external": true,
      "loc": "mm/shuffle.c:186",
      "file": "mm/shuffle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504160,
      "name": "add_to_free_area_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void add_to_free_area_random(struct page * page, struct free_area * area, int migratetype)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void add_to_free_area_random(struct page * page, struct free_area * area, int migratetype)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
