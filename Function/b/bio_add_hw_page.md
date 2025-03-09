# Function: <code>bio_add_hw_page</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int bio_add_hw_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool * same_page)
```

```json
{
  "name": "bio_add_hw_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347296,
      "name": "bio_add_hw_page",
      "external": true,
      "loc": "block/bio.c:790",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:bio_add_pc_page",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347296,
      "name": "bio_add_hw_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int bio_add_hw_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool * same_page)
```

```json
{
  "name": "bio_add_hw_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584464048,
      "name": "bio_add_hw_page",
      "external": true,
      "loc": "block/bio.c:790",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:bio_add_pc_page",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584464048,
      "name": "bio_add_hw_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int bio_add_hw_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool * same_page)
```

```json
{
  "name": "bio_add_hw_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498448,
      "name": "bio_add_hw_page",
      "external": true,
      "loc": "block/bio.c:746",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_add_zone_append_page",
        "block/bio.c:bio_add_pc_page",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498448,
      "name": "bio_add_hw_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bio_add_hw_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool * same_page)
```

```json
{
  "name": "bio_add_hw_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584909216,
      "name": "bio_add_hw_page",
      "external": true,
      "loc": "block/bio.c:829",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:bio_add_zone_append_page",
        "block/bio.c:bio_add_pc_page",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584909216,
      "name": "bio_add_hw_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int bio_add_hw_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool * same_page)
```

```json
{
  "name": "bio_add_hw_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585609248,
      "name": "bio_add_hw_page",
      "external": true,
      "loc": "block/bio.c:947",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_iov_iter_get_pages",
        "block/bio.c:bio_add_zone_append_page",
        "block/bio.c:bio_add_pc_page",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609248,
      "name": "bio_add_hw_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
int bio_add_hw_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool * same_page)
```

```json
{
  "name": "bio_add_hw_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586378208,
      "name": "bio_add_hw_page",
      "external": true,
      "loc": "block/bio.c:1002",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:bio_add_zone_append_page",
        "block/bio.c:bio_add_pc_page",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586378208,
      "name": "bio_add_hw_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
int bio_add_hw_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool * same_page)
```

```json
{
  "name": "bio_add_hw_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586624784,
      "name": "bio_add_hw_page",
      "external": true,
      "loc": "block/bio.c:965",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:bio_add_zone_append_page",
        "block/bio.c:bio_add_pc_page",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586624784,
      "name": "bio_add_hw_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int bio_add_hw_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool * same_page)
```

```json
{
  "name": "bio_add_hw_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586896288,
      "name": "bio_add_hw_page",
      "external": true,
      "loc": "block/bio.c:965",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:bio_add_zone_append_page",
        "block/bio.c:bio_add_pc_page",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586896288,
      "name": "bio_add_hw_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bio_add_hw_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool * same_page)
```
</details>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
