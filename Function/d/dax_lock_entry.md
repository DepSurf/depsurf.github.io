# Function: <code>dax_lock_entry</code>

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
void * dax_lock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582040816,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:289",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040816,
      "name": "dax_lock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void * dax_lock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582201904,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:294",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201904,
      "name": "dax_lock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582289211,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:295",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582576561,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:295",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582647917,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:295",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582674349,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:306",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583001710,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:306",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583471697,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:306",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
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
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584065054,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:306",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_mapping_entry",
        "fs/dax.c:dax_lock_page"
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
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584291464,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:306",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_mapping_entry",
        "fs/dax.c:dax_lock_page"
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
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584508268,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:292",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_mapping_entry",
        "fs/dax.c:dax_lock_folio"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493863400,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:295",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_lock_page"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * dax_lock_entry(struct xa_state * xas, void * entry)
```

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287485104,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:295",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287485104,
      "name": "dax_lock_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273429764,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:295",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_lock_page"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582257947,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:295",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582194923,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:295",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582248427,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:295",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_lock_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582323145,
      "name": "dax_lock_entry",
      "external": false,
      "loc": "fs/dax.c:295",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void * dax_lock_entry(struct xa_state * xas, void * entry)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void * dax_lock_entry(struct xa_state * xas, void * entry)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void * dax_lock_entry(struct xa_state * xas, void * entry)
```
</details>
</li>
</ul>
