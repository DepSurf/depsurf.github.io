# Function: <code>do_page_cache_ra</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void do_page_cache_ra(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
```

```json
{
  "name": "do_page_cache_ra",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581365455,
      "name": "do_page_cache_ra",
      "external": true,
      "loc": "mm/readahead.c:249",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra"
      ],
      "caller_func": [
        "mm/filemap.c:do_sync_mmap_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366144,
      "name": "do_page_cache_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void do_page_cache_ra(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
```

```json
{
  "name": "do_page_cache_ra",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581384986,
      "name": "do_page_cache_ra",
      "external": true,
      "loc": "mm/readahead.c:249",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385616,
      "name": "do_page_cache_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void do_page_cache_ra(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
```

```json
{
  "name": "do_page_cache_ra",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581633987,
      "name": "do_page_cache_ra",
      "external": true,
      "loc": "mm/readahead.c:251",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:force_page_cache_ra"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634720,
      "name": "do_page_cache_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_page_cache_ra",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581999882,
      "name": "do_page_cache_ra",
      "external": false,
      "loc": "mm/readahead.c:275",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:force_page_cache_ra"
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
  "name": "do_page_cache_ra",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582436006,
      "name": "do_page_cache_ra",
      "external": false,
      "loc": "mm/readahead.c:282",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:force_page_cache_ra"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_page_cache_ra",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582641408,
      "name": "do_page_cache_ra",
      "external": false,
      "loc": "mm/readahead.c:281",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:force_page_cache_ra"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_page_cache_ra",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582812517,
      "name": "do_page_cache_ra",
      "external": false,
      "loc": "mm/readahead.c:281",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/readahead.c:ondemand_readahead",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:force_page_cache_ra"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void do_page_cache_ra(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
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
void do_page_cache_ra(struct readahead_control * ractl, long unsigned int nr_to_read, long unsigned int lookahead_size)
```
</details>
</li>
</ul>
