# Function: <code>bio_associate_blkg_from_page</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583669856,
      "name": "bio_associate_blkg_from_page",
      "external": true,
      "loc": "block/bio.c:2051",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583669856,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583858432,
      "name": "bio_associate_blkg_from_page",
      "external": true,
      "loc": "block/bio.c:2085",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858432,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583961088,
      "name": "bio_associate_blkg_from_page",
      "external": true,
      "loc": "block/bio.c:2127",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961088,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584349008,
      "name": "bio_associate_blkg_from_page",
      "external": true,
      "loc": "block/bio.c:1706",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584349008,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581743304,
      "name": "bio_associate_blkg_from_page",
      "external": false,
      "loc": "mm/page_io.c:286",
      "file": "mm/page_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581771385,
      "name": "bio_associate_blkg_from_page",
      "external": false,
      "loc": "mm/page_io.c:267",
      "file": "mm/page_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582054006,
      "name": "bio_associate_blkg_from_page",
      "external": false,
      "loc": "mm/page_io.c:267",
      "file": "mm/page_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582489264,
      "name": "bio_associate_blkg_from_page",
      "external": false,
      "loc": "mm/page_io.c:220",
      "file": "mm/page_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583004810,
      "name": "bio_associate_blkg_from_page",
      "external": false,
      "loc": "mm/page_io.c:221",
      "file": "mm/page_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583210560,
      "name": "bio_associate_blkg_from_page",
      "external": false,
      "loc": "mm/page_io.c:221",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage_bdev_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583210560,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583445136,
      "name": "bio_associate_blkg_from_page",
      "external": false,
      "loc": "mm/page_io.c:225",
      "file": "mm/page_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage_bdev_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445136,
      "name": "bio_associate_blkg_from_page.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495783000,
      "name": "bio_associate_blkg_from_page",
      "external": true,
      "loc": "block/bio.c:2127",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495783000,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229134756,
      "name": "bio_associate_blkg_from_page",
      "external": true,
      "loc": "block/bio.c:2127",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229134756,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289959840,
      "name": "bio_associate_blkg_from_page",
      "external": true,
      "loc": "block/bio.c:2127",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289959840,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274926520,
      "name": "bio_associate_blkg_from_page",
      "external": true,
      "loc": "block/bio.c:2127",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274926520,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583929824,
      "name": "bio_associate_blkg_from_page",
      "external": true,
      "loc": "block/bio.c:2127",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929824,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583866768,
      "name": "bio_associate_blkg_from_page",
      "external": true,
      "loc": "block/bio.c:2127",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866768,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583913584,
      "name": "bio_associate_blkg_from_page",
      "external": true,
      "loc": "block/bio.c:2127",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583913584,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```

```json
{
  "name": "bio_associate_blkg_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584014976,
      "name": "bio_associate_blkg_from_page",
      "external": true,
      "loc": "block/bio.c:2127",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014976,
      "name": "bio_associate_blkg_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void bio_associate_blkg_from_page(struct bio * bio, struct page * page)
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
