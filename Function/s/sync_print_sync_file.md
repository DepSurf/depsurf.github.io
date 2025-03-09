# Function: <code>sync_print_sync_file</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585319767,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:133",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585407072,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:132",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585407072,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585837168,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:130",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585837168,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586084208,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:130",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586084208,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586228480,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:130",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228480,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586472320,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586472320,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586620112,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586620112,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587415024,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587415024,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587484752,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587484752,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587366368,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587366368,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587933360,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587933360,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589286656,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589286656,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590848512,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590848512,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591191040,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591191040,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591537952,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591537952,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499510968,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499510968,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231980076,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231980076,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292799328,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292799328,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276720858,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276720858,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586310592,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586310592,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586151936,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151936,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586568080,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586568080,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```

```json
{
  "name": "sync_print_sync_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586680352,
      "name": "sync_print_sync_file",
      "external": false,
      "loc": "drivers/dma-buf/sync_debug.c:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586680352,
      "name": "sync_print_sync_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void sync_print_sync_file(struct seq_file * s, struct sync_file * sync_file)
```
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
