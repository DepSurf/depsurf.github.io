# Function: <code>dax_wake_mapping_entry_waiter</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void dax_wake_mapping_entry_waiter(struct address_space * mapping, long unsigned int index, bool wake_all)
```

```json
{
  "name": "dax_wake_mapping_entry_waiter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581497168,
      "name": "dax_wake_mapping_entry_waiter",
      "external": true,
      "loc": "fs/dax.c:463",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_cache_tree_insert",
        "fs/dax.c:dax_pfn_mkwrite",
        "fs/dax.c:dax_delete_mapping_entry",
        "fs/dax.c:dax_unlock_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581497168,
      "name": "dax_wake_mapping_entry_waiter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void dax_wake_mapping_entry_waiter(struct address_space * mapping, long unsigned int index, void * entry, bool wake_all)
```

```json
{
  "name": "dax_wake_mapping_entry_waiter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581578000,
      "name": "dax_wake_mapping_entry_waiter",
      "external": true,
      "loc": "fs/dax.c:436",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_cache_tree_insert",
        "fs/dax.c:dax_invalidate_mapping_entry",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_unlock_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578000,
      "name": "dax_wake_mapping_entry_waiter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void dax_wake_mapping_entry_waiter(struct address_space * mapping, long unsigned int index, void * entry, bool wake_all)
```

```json
{
  "name": "dax_wake_mapping_entry_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581635472,
      "name": "dax_wake_mapping_entry_waiter",
      "external": false,
      "loc": "fs/dax.c:164",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_unlock_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635472,
      "name": "dax_wake_mapping_entry_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void dax_wake_mapping_entry_waiter(struct address_space * mapping, long unsigned int index, void * entry, bool wake_all)
```

```json
{
  "name": "dax_wake_mapping_entry_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780064,
      "name": "dax_wake_mapping_entry_waiter",
      "external": false,
      "loc": "fs/dax.c:167",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_unlock_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780064,
      "name": "dax_wake_mapping_entry_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void dax_wake_mapping_entry_waiter(struct address_space * mapping, long unsigned int index, void * entry, bool wake_all)
```

```json
{
  "name": "dax_wake_mapping_entry_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581953056,
      "name": "dax_wake_mapping_entry_waiter",
      "external": false,
      "loc": "fs/dax.c:165",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:unlock_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953056,
      "name": "dax_wake_mapping_entry_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void dax_wake_mapping_entry_waiter(struct address_space * mapping, long unsigned int index, bool wake_all)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * entry</code>
</li>
<li>
<b>Param reordered. </b>
<code>mapping, index, wake_all</code> ➡️ <code>mapping, index, entry, wake_all</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void dax_wake_mapping_entry_waiter(struct address_space * mapping, long unsigned int index, void * entry, bool wake_all)
```
</details>
</li>
</ul>
