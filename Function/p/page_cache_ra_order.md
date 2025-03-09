# Function: <code>page_cache_ra_order</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void page_cache_ra_order(struct readahead_control * ractl, struct file_ra_state * ra, unsigned int new_order)
```

```json
{
  "name": "page_cache_ra_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_cache_ra_order",
      "external": true,
      "loc": "mm/readahead.c:490",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/readahead.c:ondemand_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593966744,
      "name": "page_cache_ra_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071581997984,
      "name": "page_cache_ra_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
void page_cache_ra_order(struct readahead_control * ractl, struct file_ra_state * ra, unsigned int new_order)
```

```json
{
  "name": "page_cache_ra_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_cache_ra_order",
      "external": true,
      "loc": "mm/readahead.c:500",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/readahead.c:ondemand_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596025089,
      "name": "page_cache_ra_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    },
    {
      "addr": 18446744071582434064,
      "name": "page_cache_ra_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 857
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
void page_cache_ra_order(struct readahead_control * ractl, struct file_ra_state * ra, unsigned int new_order)
```

```json
{
  "name": "page_cache_ra_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_cache_ra_order",
      "external": true,
      "loc": "mm/readahead.c:499",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/readahead.c:ondemand_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596547312,
      "name": "page_cache_ra_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071582639392,
      "name": "page_cache_ra_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 894
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
void page_cache_ra_order(struct readahead_control * ractl, struct file_ra_state * ra, unsigned int new_order)
```

```json
{
  "name": "page_cache_ra_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_cache_ra_order",
      "external": true,
      "loc": "mm/readahead.c:486",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/readahead.c:ondemand_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597451029,
      "name": "page_cache_ra_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071582810560,
      "name": "page_cache_ra_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 846
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void page_cache_ra_order(struct readahead_control * ractl, struct file_ra_state * ra, unsigned int new_order)
```
</details>
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
