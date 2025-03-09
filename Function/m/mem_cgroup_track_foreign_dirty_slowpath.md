# Function: <code>mem_cgroup_track_foreign_dirty_slowpath</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759760,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4503",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759760,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581979552,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4383",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979552,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582029856,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4648",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029856,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582056032,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4416",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056032,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582363904,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4583",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582363904,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
void mem_cgroup_track_foreign_dirty_slowpath(struct folio * folio, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582861232,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4534",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_account_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582861232,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
void mem_cgroup_track_foreign_dirty_slowpath(struct folio * folio, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583408608,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4644",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_account_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408608,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
void mem_cgroup_track_foreign_dirty_slowpath(struct folio * folio, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583628864,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4668",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_account_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583628864,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
void mem_cgroup_track_foreign_dirty_slowpath(struct folio * folio, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583823440,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4865",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_account_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823440,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493213496,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4503",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493213496,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226844252,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4503",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226844252,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286724992,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4503",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286724992,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272990088,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4503",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272990088,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581728496,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4503",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581728496,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581667264,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4503",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581667264,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581719808,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4503",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581719808,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```

```json
{
  "name": "mem_cgroup_track_foreign_dirty_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581787744,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "external": true,
      "loc": "mm/memcontrol.c:4503",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787744,
      "name": "mem_cgroup_track_foreign_dirty_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page * page, struct bdi_writeback * wb)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
