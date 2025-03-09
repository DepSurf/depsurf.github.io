# Function: <code>force_page_cache_ra</code>

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
void force_page_cache_ra(struct readahead_control * ractl, struct file_ra_state * ra, long unsigned int nr_to_read)
```

```json
{
  "name": "force_page_cache_ra",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581366208,
      "name": "force_page_cache_ra",
      "external": true,
      "loc": "mm/readahead.c:274",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/readahead.c:page_cache_sync_ra"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366208,
      "name": "force_page_cache_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void force_page_cache_ra(struct readahead_control * ractl, long unsigned int nr_to_read)
```

```json
{
  "name": "force_page_cache_ra",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581385680,
      "name": "force_page_cache_ra",
      "external": true,
      "loc": "mm/readahead.c:274",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/readahead.c:page_cache_sync_ra"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385680,
      "name": "force_page_cache_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void force_page_cache_ra(struct readahead_control * ractl, long unsigned int nr_to_read)
```

```json
{
  "name": "force_page_cache_ra",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581634784,
      "name": "force_page_cache_ra",
      "external": true,
      "loc": "mm/readahead.c:276",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/readahead.c:page_cache_sync_ra"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634784,
      "name": "force_page_cache_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void force_page_cache_ra(struct readahead_control * ractl, long unsigned int nr_to_read)
```

```json
{
  "name": "force_page_cache_ra",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581997776,
      "name": "force_page_cache_ra",
      "external": true,
      "loc": "mm/readahead.c:300",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/readahead.c:page_cache_sync_ra"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997776,
      "name": "force_page_cache_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void force_page_cache_ra(struct readahead_control * ractl, long unsigned int nr_to_read)
```

```json
{
  "name": "force_page_cache_ra",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433840,
      "name": "force_page_cache_ra",
      "external": true,
      "loc": "mm/readahead.c:307",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/readahead.c:page_cache_sync_ra"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433840,
      "name": "force_page_cache_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void force_page_cache_ra(struct readahead_control * ractl, long unsigned int nr_to_read)
```

```json
{
  "name": "force_page_cache_ra",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582639168,
      "name": "force_page_cache_ra",
      "external": true,
      "loc": "mm/readahead.c:306",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/readahead.c:page_cache_sync_ra"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582639168,
      "name": "force_page_cache_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void force_page_cache_ra(struct readahead_control * ractl, long unsigned int nr_to_read)
```

```json
{
  "name": "force_page_cache_ra",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582810336,
      "name": "force_page_cache_ra",
      "external": true,
      "loc": "mm/readahead.c:306",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/readahead.c:page_cache_sync_ra"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582810336,
      "name": "force_page_cache_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void force_page_cache_ra(struct readahead_control * ractl, struct file_ra_state * ra, long unsigned int nr_to_read)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct file_ra_state * ra</code>
</li>
<li>
<b>Param reordered. </b>
<code>ractl, ra, nr_to_read</code> ➡️ <code>ractl, nr_to_read</code>
</li>
</ul>
</details>
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
