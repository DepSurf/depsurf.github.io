# Function: <code>release_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void release_pages(struct page * * pages, int nr, bool cold)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538880,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:909",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__pagevec_release",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538880,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
void release_pages(struct page * * pages, int nr, bool cold)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625328,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:729",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625328,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
void release_pages(struct page * * pages, int nr, bool cold)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692544,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:730",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692544,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 853
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
void release_pages(struct page * * pages, int nr, bool cold)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726432,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:743",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726432,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580813360,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:743",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580813360,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 977
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950704,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:715",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950704,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1002
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581026864,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:717",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026864,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1007
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581088976,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:718",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581088976,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1013
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145696,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:760",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145696,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1013
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328928,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:827",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328928,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1055
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581370080,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:856",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370080,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581394000,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:895",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581394000,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1191
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581643856,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:886",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643856,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1282
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582011936,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:900",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/mlock.c:mlock_pagevec",
        "mm/swap_state.c:free_pages_and_swap_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582011936,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1581
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
void release_pages(release_pages_arg arg, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582446704,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:994",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:folio_batch_move_lru",
        "mm/mlock.c:mlock_pagevec",
        "mm/swap_state.c:free_pages_and_swap_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446704,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1304
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
void release_pages(release_pages_arg arg, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582651792,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:960",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__folio_batch_release",
        "mm/swap.c:folio_batch_move_lru",
        "mm/mlock.c:mlock_folio_batch",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/splice.c:copy_splice_read",
        "fs/splice.c:copy_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582651792,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1304
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
void release_pages(release_pages_arg arg, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582822928,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:960",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__folio_batch_release",
        "mm/swap.c:folio_batch_move_lru",
        "mm/mlock.c:mlock_folio_batch",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/splice.c:copy_splice_read",
        "fs/splice.c:copy_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582822928,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1315
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492521200,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:760",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492521200,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1104
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226389084,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:760",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_retrieve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226389084,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285814336,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:760",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285814336,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1548
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272575546,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:760",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272575546,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581114544,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:760",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114544,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1013
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581061584,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:760",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581061584,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1013
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105744,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:760",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105744,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1013
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
void release_pages(struct page * * pages, int nr)
```

```json
{
  "name": "release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168016,
      "name": "release_pages",
      "external": true,
      "loc": "mm/swap.c:760",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168016,
      "name": "release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1013
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool cold</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>release_pages_arg arg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * * pages</code>
</li>
</ul>
</details>
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
