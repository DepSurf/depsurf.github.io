# Function: <code>__munlock_isolation_failed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580692372,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:147",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580805632,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:150",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805632,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580870688,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:150",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870688,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915632,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:149",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915632,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581015008,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:150",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581015008,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581149472,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149472,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581229408,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229408,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581303136,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303136,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361712,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361712,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581559827,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581603584,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:139",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581603584,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626048,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:139",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626048,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581893520,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:140",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581893520,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492766624,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
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
      "addr": 18446603336492766624,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226586152,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
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
      "addr": 3226586152,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286131728,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
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
      "addr": 13835058055286131728,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272744628,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
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
      "addr": 18446743936272744628,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581330560,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330560,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581274288,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274288,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321760,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321760,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void __munlock_isolation_failed(struct page * page)
```

```json
{
  "name": "__munlock_isolation_failed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581385728,
      "name": "__munlock_isolation_failed",
      "external": false,
      "loc": "mm/mlock.c:156",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385728,
      "name": "__munlock_isolation_failed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void __munlock_isolation_failed(struct page * page)
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
void __munlock_isolation_failed(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __munlock_isolation_failed(struct page * page)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __munlock_isolation_failed(struct page * page)
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
