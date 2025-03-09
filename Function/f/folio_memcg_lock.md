# Function: <code>folio_memcg_lock</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void folio_memcg_lock(struct folio * folio)
```

```json
{
  "name": "folio_memcg_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582844775,
      "name": "folio_memcg_lock",
      "external": true,
      "loc": "mm/memcontrol.c:2032",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:lock_page_memcg"
      ],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:__folio_cancel_dirty",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:lock_page_memcg",
        "fs/buffer.c:block_dirty_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817376,
      "name": "folio_memcg_lock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071582850544,
      "name": "folio_memcg_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void folio_memcg_lock(struct folio * folio)
```

```json
{
  "name": "folio_memcg_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583391296,
      "name": "folio_memcg_lock",
      "external": true,
      "loc": "mm/memcontrol.c:2092",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:lock_page_memcg"
      ],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:__folio_cancel_dirty",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:lock_page_memcg",
        "fs/buffer.c:block_dirty_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583363616,
      "name": "folio_memcg_lock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071583397088,
      "name": "folio_memcg_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void folio_memcg_lock(struct folio * folio)
```

```json
{
  "name": "folio_memcg_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583616320,
      "name": "folio_memcg_lock",
      "external": true,
      "loc": "mm/memcontrol.c:2112",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:__folio_cancel_dirty",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:block_dirty_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616320,
      "name": "folio_memcg_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void folio_memcg_lock(struct folio * folio)
```

```json
{
  "name": "folio_memcg_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583811200,
      "name": "folio_memcg_lock",
      "external": true,
      "loc": "mm/memcontrol.c:2184",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:__folio_cancel_dirty",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:block_dirty_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583811200,
      "name": "folio_memcg_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void folio_memcg_lock(struct folio * folio)
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
