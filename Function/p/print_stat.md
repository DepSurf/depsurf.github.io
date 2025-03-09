# Function: <code>print_stat</code>

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
  "name": "print_stat",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583146283,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-sysfs.c:500",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_stats_show",
        "block/blk-sysfs.c:queue_stats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583199191,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-sysfs.c:280",
      "file": "block/blk-mq-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_stat_show",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_stat_show"
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406288,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:130",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406288,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583585872,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:128",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585872,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583802288,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:27",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583802288,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583884560,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:28",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583884560,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584075216,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075216,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584197920,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197920,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584595503,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
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
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584714479,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
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
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584742639,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
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
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585170663,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
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
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585906600,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:18",
      "file": "block/blk-mq-debugfs.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586695464,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:18",
      "file": "block/blk-mq-debugfs.c",
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496066024,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496066024,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229395144,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229395144,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290302336,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290302336,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275139672,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275139672,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584166656,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584166656,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584101904,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101904,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584150416,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584150416,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
```

```json
{
  "name": "print_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584254896,
      "name": "print_stat",
      "external": false,
      "loc": "block/blk-mq-debugfs.c:17",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_poll_stat_show",
        "block/blk-mq-debugfs.c:queue_poll_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254896,
      "name": "print_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void print_stat(struct seq_file * m, struct blk_rq_stat * stat)
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
