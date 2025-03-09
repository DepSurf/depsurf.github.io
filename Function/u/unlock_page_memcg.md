# Function: <code>unlock_page_memcg</code>

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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581061264,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1697",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581061264,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136528,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1668",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136528,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188304,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1690",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188304,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317408,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1704",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317408,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463616,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1661",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463616,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581547824,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:1939",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap.c:iomap_set_page_dirty",
        "fs/iomap.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581547824,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684320,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2140",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684320,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756752,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2156",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756752,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581952704,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2031",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581952704,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581998896,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2226",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581998896,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582022320,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2035",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582022320,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582326528,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2087",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582326528,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582850816,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2108",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582850816,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583397408,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2168",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583397408,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493210400,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2156",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493210400,
      "name": "unlock_page_memcg",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226840704,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2156",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226840704,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286719984,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2156",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286719984,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272987060,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2156",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272987060,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725488,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2156",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725488,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664288,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2156",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664288,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716800,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2156",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716800,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void unlock_page_memcg(struct page * page)
```

```json
{
  "name": "unlock_page_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784464,
      "name": "unlock_page_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2156",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/rmap.c:page_add_file_rmap",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784464,
      "name": "unlock_page_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void unlock_page_memcg(struct page * page)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void unlock_page_memcg(struct page * page)
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
