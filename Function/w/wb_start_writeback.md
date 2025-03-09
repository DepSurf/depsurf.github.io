# Function: <code>wb_start_writeback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, long int nr_pages, bool range_cyclic, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581189056,
      "name": "wb_start_writeback",
      "external": true,
      "loc": "fs/fs-writeback.c:922",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:laptop_mode_timer_fn",
        "fs/fs-writeback.c:wakeup_flusher_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189056,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, long int nr_pages, bool range_cyclic, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581352496,
      "name": "wb_start_writeback",
      "external": true,
      "loc": "fs/fs-writeback.c:922",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:laptop_mode_timer_fn",
        "fs/fs-writeback.c:wakeup_flusher_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352496,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void wb_start_writeback(struct bdi_writeback * wb, long int nr_pages, bool range_cyclic, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581431408,
      "name": "wb_start_writeback",
      "external": true,
      "loc": "fs/fs-writeback.c:922",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:laptop_mode_timer_fn",
        "fs/fs-writeback.c:wakeup_flusher_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431408,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void wb_start_writeback(struct bdi_writeback * wb, long int nr_pages, bool range_cyclic, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581485584,
      "name": "wb_start_writeback",
      "external": true,
      "loc": "fs/fs-writeback.c:936",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:laptop_mode_timer_fn",
        "fs/fs-writeback.c:wakeup_flusher_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485584,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581610923,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:947",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581769211,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:948",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581854032,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:974",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581854032,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978688,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:989",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978688,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582053680,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1077",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053680,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582313618,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1077",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582366482,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1077",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582394146,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1083",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582715682,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1222",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583260086,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1188",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583824176,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1191",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824176,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584041520,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1196",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584041520,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584256320,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1213",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584256320,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493592360,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1077",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227130132,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1077",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287162672,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1077",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287162672,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273236410,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1077",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582022416,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1077",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582022416,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581959984,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1077",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581959984,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582013696,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1077",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582013696,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```

```json
{
  "name": "wb_start_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582084208,
      "name": "wb_start_writeback",
      "external": false,
      "loc": "fs/fs-writeback.c:1077",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582084208,
      "name": "wb_start_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, long int nr_pages, bool range_cyclic, enum wb_reason reason)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void wb_start_writeback(struct bdi_writeback * wb, enum wb_reason reason)
```
</details>
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
