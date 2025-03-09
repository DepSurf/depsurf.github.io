# Function: <code>swapcache_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void swapcache_free(swp_entry_t entry)
```

```json
{
  "name": "swapcache_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764064,
      "name": "swapcache_free",
      "external": true,
      "loc": "mm/swapfile.c:852",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:__read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764064,
      "name": "swapcache_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void swapcache_free(swp_entry_t entry)
```

```json
{
  "name": "swapcache_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580886640,
      "name": "swapcache_free",
      "external": true,
      "loc": "mm/swapfile.c:847",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886640,
      "name": "swapcache_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void swapcache_free(swp_entry_t entry)
```

```json
{
  "name": "swapcache_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954736,
      "name": "swapcache_free",
      "external": true,
      "loc": "mm/swapfile.c:853",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954736,
      "name": "swapcache_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swapcache_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580999852,
      "name": "swapcache_free",
      "external": false,
      "loc": "mm/swapfile.c:1152",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:put_swap_page"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swapcache_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581111587,
      "name": "swapcache_free",
      "external": false,
      "loc": "mm/swapfile.c:1187",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:put_swap_page"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swapcache_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581247233,
      "name": "swapcache_free",
      "external": false,
      "loc": "mm/swapfile.c:1187",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:put_swap_page"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void swapcache_free(swp_entry_t entry)
```
</details>
</li>
</ul>
