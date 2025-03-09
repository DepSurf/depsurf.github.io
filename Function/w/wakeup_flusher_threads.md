# Function: <code>wakeup_flusher_threads</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void wakeup_flusher_threads(long int nr_pages, enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581190544,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:1900",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "fs/sync.c:sys_sync",
        "fs/buffer.c:free_more_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190544,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void wakeup_flusher_threads(long int nr_pages, enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581354448,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:1948",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "fs/sync.c:sys_sync",
        "fs/buffer.c:free_more_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581354448,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
void wakeup_flusher_threads(long int nr_pages, enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433360,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:1946",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "fs/sync.c:sys_sync",
        "fs/buffer.c:free_more_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433360,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
void wakeup_flusher_threads(long int nr_pages, enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487376,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:1953",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:sys_sync",
        "fs/buffer.c:free_more_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487376,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581629504,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:1997",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581629504,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581788112,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:1998",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788112,
      "name": "wakeup_flusher_threads",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581874960,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2024",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874960,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581999792,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2039",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999792,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582077888,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2127",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582077888,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313472,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2135",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313472,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582366336,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2131",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582366336,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582394000,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2146",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582394000,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582715536,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2286",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582715536,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259968,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2269",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259968,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583841616,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2293",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841616,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584059712,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2304",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584059712,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584274848,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2326",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584274848,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493610528,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2127",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493610528,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227154996,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2127",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227154996,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287198400,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2127",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287198400,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273257594,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2127",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273257594,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582046624,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2127",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582046624,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581984176,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2127",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581984176,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582037904,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2127",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582037904,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void wakeup_flusher_threads(enum wb_reason reason)
```

```json
{
  "name": "wakeup_flusher_threads",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109616,
      "name": "wakeup_flusher_threads",
      "external": true,
      "loc": "fs/fs-writeback.c:2127",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/vmscan.c:shrink_inactive_list",
        "fs/sync.c:ksys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109616,
      "name": "wakeup_flusher_threads",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
<code>long int nr_pages</code>
</li>
<li>
<b>Param reordered. </b>
<code>nr_pages, reason</code> ➡️ <code>reason</code>
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
