# Function: <code>get_swap_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580753856,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:27",
      "file": "mm/page_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753856,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580875552,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:27",
      "file": "mm/page_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875552,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580943552,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:27",
      "file": "mm/page_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943552,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580987680,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:28",
      "file": "mm/page_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580987680,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090976,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090976,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581231520,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581231520,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314496,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314496,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581425584,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581425584,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581489808,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581489808,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694848,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694848,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581741632,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741632,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492907944,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492907944,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226699548,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226699548,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286312064,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286312064,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272832038,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272832038,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581458656,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458656,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400848,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400848,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449856,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581449856,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
```

```json
{
  "name": "get_swap_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581514336,
      "name": "get_swap_bio",
      "external": false,
      "loc": "mm/page_io.c:29",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514336,
      "name": "get_swap_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct bio * get_swap_bio(gfp_t gfp_flags, struct page * page, bio_end_io_t * end_io)
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
