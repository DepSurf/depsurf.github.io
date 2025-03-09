# Function: <code>sync_print_fence</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585319008,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:74",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319008,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585406640,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:74",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585406640,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585836736,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:74",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585836736,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:74",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586083776,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071586085261,
      "name": "sync_print_fence.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:74",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228048,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071586229533,
      "name": "sync_print_fence.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586471872,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071586473200,
      "name": "sync_print_fence.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586619664,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071586620992,
      "name": "sync_print_fence.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587414576,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071587415923,
      "name": "sync_print_fence.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587484304,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071591518845,
      "name": "sync_print_fence.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587365920,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071591460739,
      "name": "sync_print_fence.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587932912,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071592525227,
      "name": "sync_print_fence.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589286160,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071594396683,
      "name": "sync_print_fence.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590847984,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590847984,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591190512,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591190512,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591537424,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591537424,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499510400,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499510400,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231979492,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231979492,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292798576,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292798576,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276720424,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276720424,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586310144,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071586311472,
      "name": "sync_print_fence.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151488,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071586152800,
      "name": "sync_print_fence.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586567632,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071586568960,
      "name": "sync_print_fence.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
```

```json
{
  "name": "sync_print_fence",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_print_fence",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:65",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file",
        "drivers/dma-buf/sync_debug.c:sync_print_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586679904,
      "name": "sync_print_fence",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071586681200,
      "name": "sync_print_fence.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void sync_print_fence(struct seq_file * s, struct dma_fence * fence, bool show)
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
