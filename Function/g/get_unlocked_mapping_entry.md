# Function: <code>get_unlocked_mapping_entry</code>

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
void * get_unlocked_mapping_entry(struct address_space * mapping, long unsigned int index, void * * * slotp)
```

```json
{
  "name": "get_unlocked_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581495648,
      "name": "get_unlocked_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:370",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_pfn_mkwrite",
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_delete_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581495648,
      "name": "get_unlocked_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
void * get_unlocked_mapping_entry(struct address_space * mapping, long unsigned int index, void * * * slotp)
```

```json
{
  "name": "get_unlocked_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576624,
      "name": "get_unlocked_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:214",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_pfn_mkwrite",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576624,
      "name": "get_unlocked_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
void * get_unlocked_mapping_entry(struct address_space * mapping, long unsigned int index, void * * * slotp)
```

```json
{
  "name": "get_unlocked_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581638288,
      "name": "get_unlocked_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:230",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581638288,
      "name": "get_unlocked_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
void * get_unlocked_mapping_entry(struct address_space * mapping, long unsigned int index, void * * * slotp)
```

```json
{
  "name": "get_unlocked_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783104,
      "name": "get_unlocked_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:233",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783104,
      "name": "get_unlocked_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_unlocked_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581958357,
      "name": "get_unlocked_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:274",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry"
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void * get_unlocked_mapping_entry(struct address_space * mapping, long unsigned int index, void * * * slotp)
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
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void * get_unlocked_mapping_entry(struct address_space * mapping, long unsigned int index, void * * * slotp)
```
</details>
</li>
</ul>
