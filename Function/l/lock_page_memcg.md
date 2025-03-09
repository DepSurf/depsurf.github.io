# Function: <code>lock_page_memcg</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581064960,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1653",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064960,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581140192,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1624",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140192,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581187536,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1620",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187536,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581316592,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1634",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316592,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581462800,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1591",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462800,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581546832,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1869",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546832,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581659008,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2070",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581659008,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581731296,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2086",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731296,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954304,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1960",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954304,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582000480,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2149",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000480,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026752,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1971",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026752,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582329216,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2023",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329216,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582850592,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2076",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "fs/buffer.c:mark_buffer_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582850592,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583397152,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2136",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "fs/buffer.c:mark_buffer_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583397152,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493187544,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2086",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493187544,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226815152,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2086",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226815152,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286680128,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2086",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286680128,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272963846,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2086",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272963846,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581700032,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2086",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581700032,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581639248,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2086",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581639248,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581691344,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2086",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691344,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * lock_page_memcg(struct page * page)
```

```json
{
  "name": "lock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581759152,
      "name": "lock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2086",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759152,
      "name": "lock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void lock_page_memcg(struct page * page)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct mem_cgroup *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct mem_cgroup *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void lock_page_memcg(struct page * page)
```
</details>
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
