# Function: <code>__bio_try_merge_page</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583534304,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:837",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583534304,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583657792,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:763",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_readpage_actor",
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583657792,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583848096,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:766",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848096,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947952,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:800",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947952,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584339984,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:870",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page",
        "block/bio.c:bio_add_hw_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339984,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584457712,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:870",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page",
        "block/bio.c:bio_add_hw_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584457712,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584492464,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:859",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:bio_add_page",
        "block/bio.c:bio_add_hw_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584492464,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584901008,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:942",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584901008,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585601040,
      "name": "__bio_try_merge_page",
      "external": false,
      "loc": "block/bio.c:891",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_add_folio",
        "block/bio.c:bio_add_hw_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585601040,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586369024,
      "name": "__bio_try_merge_page",
      "external": false,
      "loc": "block/bio.c:946",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:bio_add_folio",
        "block/bio.c:bio_add_hw_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586369024,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    }
  ]
}
```
</details>
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495767960,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:800",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495767960,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229122228,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:800",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229122228,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289942032,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:800",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289942032,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274915362,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:800",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274915362,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916688,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:800",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916688,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583853648,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:800",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583853648,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583900448,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:800",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900448,
      "name": "__bio_try_merge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
```

```json
{
  "name": "__bio_try_merge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584001600,
      "name": "__bio_try_merge_page",
      "external": true,
      "loc": "block/bio.c:800",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001600,
      "name": "__bio_try_merge_page",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * same_page</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
bool __bio_try_merge_page(struct bio * bio, struct page * page, unsigned int len, unsigned int off, bool * same_page)
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
