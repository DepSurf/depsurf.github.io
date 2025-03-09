# Function: <code>page_cache_ra_unbounded</code>

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
void page_cache_ra_unbounded(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
```

```json
{
  "name": "page_cache_ra_unbounded",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581364576,
      "name": "page_cache_ra_unbounded",
      "external": true,
      "loc": "mm/readahead.c:174",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364576,
      "name": "page_cache_ra_unbounded",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
void page_cache_ra_unbounded(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
```

```json
{
  "name": "page_cache_ra_unbounded",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581384112,
      "name": "page_cache_ra_unbounded",
      "external": true,
      "loc": "mm/readahead.c:174",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581384112,
      "name": "page_cache_ra_unbounded",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
void page_cache_ra_unbounded(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
```

```json
{
  "name": "page_cache_ra_unbounded",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581633136,
      "name": "page_cache_ra_unbounded",
      "external": true,
      "loc": "mm/readahead.c:174",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633136,
      "name": "page_cache_ra_unbounded",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
void page_cache_ra_unbounded(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
```

```json
{
  "name": "page_cache_ra_unbounded",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581996848,
      "name": "page_cache_ra_unbounded",
      "external": true,
      "loc": "mm/readahead.c:200",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:force_page_cache_ra",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996848,
      "name": "page_cache_ra_unbounded",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void page_cache_ra_unbounded(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
```

```json
{
  "name": "page_cache_ra_unbounded",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_cache_ra_unbounded",
      "external": true,
      "loc": "mm/readahead.c:206",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:force_page_cache_ra",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596025041,
      "name": "page_cache_ra_unbounded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071582432688,
      "name": "page_cache_ra_unbounded",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void page_cache_ra_unbounded(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
```

```json
{
  "name": "page_cache_ra_unbounded",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_cache_ra_unbounded",
      "external": true,
      "loc": "mm/readahead.c:205",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:force_page_cache_ra",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596547244,
      "name": "page_cache_ra_unbounded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071582638144,
      "name": "page_cache_ra_unbounded",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void page_cache_ra_unbounded(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
```

```json
{
  "name": "page_cache_ra_unbounded",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_cache_ra_unbounded",
      "external": true,
      "loc": "mm/readahead.c:205",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:force_page_cache_ra",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597450961,
      "name": "page_cache_ra_unbounded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071582809312,
      "name": "page_cache_ra_unbounded",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
void page_cache_ra_unbounded(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
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
