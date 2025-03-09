# Function: <code>cgroup_writeback_by_id</code>

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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582075376,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:918",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582075376,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311376,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:919",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582311376,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582364288,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:919",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582364288,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582391936,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:925",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582391936,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582713584,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:1048",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582713584,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583257824,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:1014",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583257824,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583839568,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:1016",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign",
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583839568,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584057648,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:1021",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign",
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057648,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584272736,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:1038",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign",
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584272736,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493607136,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:918",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493607136,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227151948,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:918",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227151948,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287194400,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:918",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287194400,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 904
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273255076,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:918",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273255076,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582044112,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:918",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044112,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581981664,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:918",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981664,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035392,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:918",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035392,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
```

```json
{
  "name": "cgroup_writeback_by_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582106848,
      "name": "cgroup_writeback_by_id",
      "external": true,
      "loc": "fs/fs-writeback.c:918",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582106848,
      "name": "cgroup_writeback_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion * done)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int nr</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdi_id, memcg_id, nr, reason, done</code> ➡️ <code>bdi_id, memcg_id, reason, done</code>
</li>
</ul>
</details>
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
