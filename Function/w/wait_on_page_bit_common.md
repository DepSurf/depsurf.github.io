# Function: <code>wait_on_page_bit_common</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, bool lock)
```

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580618640,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:826",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page"
      ],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:__filemap_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580613200,
      "name": "wait_on_page_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, bool lock)
```

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580648418,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:953",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page"
      ],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642128,
      "name": "wait_on_page_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, bool lock)
```

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580732288,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1074",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page"
      ],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580724448,
      "name": "wait_on_page_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, bool lock)
```

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580867924,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1074",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page"
      ],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860224,
      "name": "wait_on_page_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, enum behavior behavior)
```

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580938988,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1074",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934320,
      "name": "wait_on_page_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581033298,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1122",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581088866,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1131",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, enum behavior behavior)
```

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267824,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1106",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267824,
      "name": "wait_on_page_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, enum behavior behavior)
```

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581312688,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1196",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read_pagenotuptodate",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312688,
      "name": "wait_on_page_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, enum behavior behavior)
```

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581331184,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1220",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:wait_on_page_private_2_killable",
        "mm/filemap.c:wait_on_page_private_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331184,
      "name": "wait_on_page_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 979
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
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, enum behavior behavior)
```

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581578880,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1275",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:wait_on_page_private_2_killable",
        "mm/filemap.c:wait_on_page_private_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578880,
      "name": "wait_on_page_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 962
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, enum behavior behavior)
```

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492446992,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1131",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492446992,
      "name": "wait_on_page_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226329096,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1131",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285730980,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1131",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272526556,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1131",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
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
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581057714,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1131",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
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
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581004962,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1131",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
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
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581048914,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1131",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
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
  "name": "wait_on_page_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581110595,
      "name": "wait_on_page_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1131",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, bool lock)
```
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum behavior behavior</code>
</li>
<li>
<b>Param removed. </b>
<code>bool lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, enum behavior behavior)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, enum behavior behavior)
```
</details>
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
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, enum behavior behavior)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int wait_on_page_bit_common(wait_queue_head_t * q, struct page * page, int bit_nr, int state, enum behavior behavior)
```
</details>
</li>
</ul>
