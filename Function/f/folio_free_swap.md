# Function: <code>folio_free_swap</code>

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
bool folio_free_swap(struct folio * folio)
```

```json
{
  "name": "folio_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583032768,
      "name": "folio_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1579",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_folio_list",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583032768,
      "name": "folio_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
bool folio_free_swap(struct folio * folio)
```

```json
{
  "name": "folio_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583241568,
      "name": "folio_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1561",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_folio_list",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583241568,
      "name": "folio_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
bool folio_free_swap(struct folio * folio)
```

```json
{
  "name": "folio_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583476048,
      "name": "folio_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1561",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_folio_list",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583476048,
      "name": "folio_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool folio_free_swap(struct folio * folio)
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
