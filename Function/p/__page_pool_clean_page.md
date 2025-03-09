# Function: <code>__page_pool_clean_page</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__page_pool_clean_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588010517,
      "name": "__page_pool_clean_page",
      "external": false,
      "loc": "net/core/page_pool.c:175",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_return_page"
      ],
      "caller_func": [
        "net/core/page_pool.c:__page_pool_return_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588010016,
      "name": "__page_pool_clean_page.isra.6.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__page_pool_clean_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588171253,
      "name": "__page_pool_clean_page",
      "external": false,
      "loc": "net/core/page_pool.c:175",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_return_page"
      ],
      "caller_func": [
        "net/core/page_pool.c:__page_pool_return_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171104,
      "name": "__page_pool_clean_page.isra.9.part.10",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __page_pool_clean_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "__page_pool_clean_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588495760,
      "name": "__page_pool_clean_page",
      "external": false,
      "loc": "net/core/page_pool.c:222",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:__page_pool_request_shutdown",
        "net/core/page_pool.c:__page_pool_request_shutdown",
        "net/core/page_pool.c:page_pool_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588495760,
      "name": "__page_pool_clean_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void __page_pool_clean_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "__page_pool_clean_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588703680,
      "name": "__page_pool_clean_page",
      "external": false,
      "loc": "net/core/page_pool.c:210",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588703680,
      "name": "__page_pool_clean_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void __page_pool_clean_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "__page_pool_clean_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502265992,
      "name": "__page_pool_clean_page",
      "external": false,
      "loc": "net/core/page_pool.c:210",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502265992,
      "name": "__page_pool_clean_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void __page_pool_clean_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "__page_pool_clean_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235007088,
      "name": "__page_pool_clean_page",
      "external": false,
      "loc": "net/core/page_pool.c:210",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235007088,
      "name": "__page_pool_clean_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void __page_pool_clean_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "__page_pool_clean_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295760816,
      "name": "__page_pool_clean_page",
      "external": false,
      "loc": "net/core/page_pool.c:210",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295760816,
      "name": "__page_pool_clean_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
void __page_pool_clean_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "__page_pool_clean_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278501474,
      "name": "__page_pool_clean_page",
      "external": false,
      "loc": "net/core/page_pool.c:210",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278501474,
      "name": "__page_pool_clean_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void __page_pool_clean_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "__page_pool_clean_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588310416,
      "name": "__page_pool_clean_page",
      "external": false,
      "loc": "net/core/page_pool.c:210",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588310416,
      "name": "__page_pool_clean_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void __page_pool_clean_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "__page_pool_clean_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588023200,
      "name": "__page_pool_clean_page",
      "external": false,
      "loc": "net/core/page_pool.c:210",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588023200,
      "name": "__page_pool_clean_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void __page_pool_clean_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "__page_pool_clean_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588642240,
      "name": "__page_pool_clean_page",
      "external": false,
      "loc": "net/core/page_pool.c:210",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588642240,
      "name": "__page_pool_clean_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void __page_pool_clean_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "__page_pool_clean_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588781728,
      "name": "__page_pool_clean_page",
      "external": false,
      "loc": "net/core/page_pool.c:210",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588781728,
      "name": "__page_pool_clean_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void __page_pool_clean_page(struct page_pool * pool, struct page * page)
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
void __page_pool_clean_page(struct page_pool * pool, struct page * page)
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
