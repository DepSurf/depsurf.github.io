# Function: <code>get_unlocked_entry</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * get_unlocked_entry(struct xa_state * xas)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582042736,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:209",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582042736,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582203920,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:212",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582203920,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582284736,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:212",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284736,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582568784,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:212",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582568784,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582640352,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:212",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640352,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669264,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:223",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669264,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582995520,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:223",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582995520,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583466160,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:223",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583466160,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584057088,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:223",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057088,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584281440,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:223",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584281440,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498240,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:209",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498240,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493858584,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:212",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493858584,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287487120,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:212",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287487120,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273426862,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:212",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273426862,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253472,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:212",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253472,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582191152,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:212",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191152,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582243952,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:212",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582243952,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```

```json
{
  "name": "get_unlocked_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318976,
      "name": "get_unlocked_entry",
      "external": false,
      "loc": "fs/dax.c:212",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318976,
      "name": "get_unlocked_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void * get_unlocked_entry(struct xa_state * xas)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int order</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * get_unlocked_entry(struct xa_state * xas, unsigned int order)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
