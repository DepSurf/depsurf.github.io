# Function: <code>__munlock_isolate_lru_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580691600,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:98",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691600,
      "name": "__munlock_isolate_lru_page.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580805168,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:101",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805168,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580870224,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:101",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870224,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915184,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:102",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915184,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581014560,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:103",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014560,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581149040,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149040,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581228976,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228976,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581303200,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303200,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581361776,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361776,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581559801,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558656,
      "name": "__munlock_isolate_lru_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492766920,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492766920,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226585768,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226585768,
      "name": "__munlock_isolate_lru_page",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286131040,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286131040,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272744300,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272744300,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581330624,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330624,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581274352,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274352,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581321824,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321824,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```

```json
{
  "name": "__munlock_isolate_lru_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581385792,
      "name": "__munlock_isolate_lru_page",
      "external": false,
      "loc": "mm/mlock.c:109",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385792,
      "name": "__munlock_isolate_lru_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool __munlock_isolate_lru_page(struct page * page, bool getpage)
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
