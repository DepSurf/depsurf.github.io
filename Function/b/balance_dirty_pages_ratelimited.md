# Function: <code>balance_dirty_pages_ratelimited</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580525600,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1820",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:handle_mm_fault",
        "fs/buffer.c:cont_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525600,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1005
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580609840,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1863",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609840,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1003
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580677088,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1864",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580677088,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709360,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1864",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709360,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580794880,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1862",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580794880,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932336,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1862",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932336,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581008912,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1861",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008912,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581072048,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1862",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072048,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 898
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581128032,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1864",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128032,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 898
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581315200,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1877",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_expand_zero",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581315200,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 894
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356464,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1877",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_expand_zero",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356464,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373376,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1877",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_expand_zero",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373376,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621824,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1878",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_expand_zero",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621824,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 967
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581985552,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1875",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_expand_zero",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581985552,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582422592,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:2062",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_expand_zero",
        "fs/iomap/buffered-io.c:iomap_file_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582422592,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582627808,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:2062",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_expand_zero",
        "fs/iomap/buffered-io.c:iomap_file_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582627808,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582799696,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:2062",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_expand_zero",
        "fs/iomap/buffered-io.c:iomap_file_unshare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799696,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492499952,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1864",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492499952,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1088
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226372604,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1864",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226372604,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1308
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285786544,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1864",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285786544,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1368
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272560354,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1864",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272560354,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 912
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096880,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1864",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096880,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 898
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581044048,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1864",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044048,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 898
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581088080,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1864",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581088080,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 898
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
void balance_dirty_pages_ratelimited(struct address_space * mapping)
```

```json
{
  "name": "balance_dirty_pages_ratelimited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581150032,
      "name": "balance_dirty_pages_ratelimited",
      "external": true,
      "loc": "mm/page-writeback.c:1864",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150032,
      "name": "balance_dirty_pages_ratelimited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1068
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
