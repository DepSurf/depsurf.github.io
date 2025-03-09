# Function: <code>dax_unlock_mapping_entry</code>

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
void dax_unlock_mapping_entry(struct address_space * mapping, long unsigned int index)
```

```json
{
  "name": "dax_unlock_mapping_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581497440,
      "name": "dax_unlock_mapping_entry",
      "external": true,
      "loc": "fs/dax.c:483",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581497440,
      "name": "dax_unlock_mapping_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void dax_unlock_mapping_entry(struct address_space * mapping, long unsigned int index)
```

```json
{
  "name": "dax_unlock_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581578400,
      "name": "dax_unlock_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:244",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_pfn_mkwrite",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578400,
      "name": "dax_unlock_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void dax_unlock_mapping_entry(struct address_space * mapping, long unsigned int index)
```

```json
{
  "name": "dax_unlock_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581639232,
      "name": "dax_unlock_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:261",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581639232,
      "name": "dax_unlock_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void dax_unlock_mapping_entry(struct address_space * mapping, long unsigned int index)
```

```json
{
  "name": "dax_unlock_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784048,
      "name": "dax_unlock_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:264",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784048,
      "name": "dax_unlock_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void dax_unlock_mapping_entry(struct page * page)
```

```json
{
  "name": "dax_unlock_mapping_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581966096,
      "name": "dax_unlock_mapping_entry",
      "external": true,
      "loc": "fs/dax.c:463",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966096,
      "name": "dax_unlock_mapping_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void dax_unlock_mapping_entry(struct address_space * mapping, long unsigned int index, dax_entry_t cookie)
```

```json
{
  "name": "dax_unlock_mapping_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068816,
      "name": "dax_unlock_mapping_entry",
      "external": true,
      "loc": "fs/dax.c:547",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:mf_dax_kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068816,
      "name": "dax_unlock_mapping_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void dax_unlock_mapping_entry(struct address_space * mapping, long unsigned int index, dax_entry_t cookie)
```

```json
{
  "name": "dax_unlock_mapping_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584295200,
      "name": "dax_unlock_mapping_entry",
      "external": true,
      "loc": "fs/dax.c:547",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:mf_dax_kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584295200,
      "name": "dax_unlock_mapping_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void dax_unlock_mapping_entry(struct address_space * mapping, long unsigned int index, dax_entry_t cookie)
```

```json
{
  "name": "dax_unlock_mapping_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584512016,
      "name": "dax_unlock_mapping_entry",
      "external": true,
      "loc": "fs/dax.c:533",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:mf_dax_kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512016,
      "name": "dax_unlock_mapping_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void dax_unlock_mapping_entry(struct address_space * mapping, long unsigned int index)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page * page</code>
</li>
<li>
<b>Param removed. </b>
<code>struct address_space * mapping</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int index</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void dax_unlock_mapping_entry(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void dax_unlock_mapping_entry(struct address_space * mapping, long unsigned int index, dax_entry_t cookie)
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
