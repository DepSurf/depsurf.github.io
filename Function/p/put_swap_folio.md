# Function: <code>put_swap_folio</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void put_swap_folio(struct folio * folio, swp_entry_t entry)
```

```json
{
  "name": "put_swap_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583030320,
      "name": "put_swap_folio",
      "external": true,
      "loc": "mm/swapfile.c:1335",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:folio_alloc_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583030320,
      "name": "put_swap_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 863
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
void put_swap_folio(struct folio * folio, swp_entry_t entry)
```

```json
{
  "name": "put_swap_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583239376,
      "name": "put_swap_folio",
      "external": true,
      "loc": "mm/swapfile.c:1341",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:folio_alloc_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583239376,
      "name": "put_swap_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
void put_swap_folio(struct folio * folio, swp_entry_t entry)
```

```json
{
  "name": "put_swap_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583473904,
      "name": "put_swap_folio",
      "external": true,
      "loc": "mm/swapfile.c:1341",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:folio_alloc_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583473904,
      "name": "put_swap_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 666
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void put_swap_folio(struct folio * folio, swp_entry_t entry)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
