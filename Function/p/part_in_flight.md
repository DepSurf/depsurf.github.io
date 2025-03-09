# Function: <code>part_in_flight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "part_in_flight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582729685,
      "name": "part_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:410",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:part_round_stats_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582819458,
      "name": "part_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:410",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582829703,
      "name": "part_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:410",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:part_stat_show"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "part_in_flight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583007429,
      "name": "part_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:394",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:part_round_stats_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098674,
      "name": "part_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:394",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583109106,
      "name": "part_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:394",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:part_stat_show"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "part_in_flight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583112421,
      "name": "part_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:385",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:part_round_stats_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583210188,
      "name": "part_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:385",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220620,
      "name": "part_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:385",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:part_stat_show"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "part_in_flight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583169317,
      "name": "part_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:379",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:part_round_stats_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583268370,
      "name": "part_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:379",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583274760,
      "name": "part_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:379",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:part_stat_show"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void part_in_flight(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583449744,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:68",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:part_round_stats",
        "block/blk-core.c:part_round_stats",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449744,
      "name": "part_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void part_in_flight(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583660976,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:68",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:part_round_stats",
        "block/blk-core.c:part_round_stats",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583660976,
      "name": "part_in_flight",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int part_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583767312,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:68",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583767312,
      "name": "part_in_flight",
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
unsigned int part_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583956784,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956784,
      "name": "part_in_flight",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int part_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584060256,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584060256,
      "name": "part_in_flight",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584454720,
      "name": "part_in_flight",
      "external": false,
      "loc": "block/genhd.c:115",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454720,
      "name": "part_in_flight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
unsigned int part_in_flight(struct block_device * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584569744,
      "name": "part_in_flight",
      "external": false,
      "loc": "block/genhd.c:133",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569744,
      "name": "part_in_flight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
unsigned int part_in_flight(struct block_device * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584602048,
      "name": "part_in_flight",
      "external": false,
      "loc": "block/genhd.c:130",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584602048,
      "name": "part_in_flight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
unsigned int part_in_flight(struct block_device * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585016224,
      "name": "part_in_flight",
      "external": false,
      "loc": "block/genhd.c:144",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585016224,
      "name": "part_in_flight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
unsigned int part_in_flight(struct block_device * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585733392,
      "name": "part_in_flight",
      "external": false,
      "loc": "block/genhd.c:148",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585733392,
      "name": "part_in_flight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
unsigned int part_in_flight(struct block_device * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586517152,
      "name": "part_in_flight",
      "external": false,
      "loc": "block/genhd.c:125",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586517152,
      "name": "part_in_flight",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
unsigned int part_in_flight(struct block_device * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764400,
      "name": "part_in_flight",
      "external": false,
      "loc": "block/genhd.c:121",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764400,
      "name": "part_in_flight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
unsigned int part_in_flight(struct block_device * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036880,
      "name": "part_in_flight",
      "external": false,
      "loc": "block/genhd.c:121",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036880,
      "name": "part_in_flight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
unsigned int part_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495901768,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495901768,
      "name": "part_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
unsigned int part_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229244848,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229244848,
      "name": "part_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
unsigned int part_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290108880,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290108880,
      "name": "part_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
unsigned int part_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275017508,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275017508,
      "name": "part_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
unsigned int part_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584028992,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028992,
      "name": "part_in_flight",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int part_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583964784,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964784,
      "name": "part_in_flight",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int part_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584012752,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012752,
      "name": "part_in_flight",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int part_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "part_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584115280,
      "name": "part_in_flight",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115280,
      "name": "part_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void part_in_flight(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int * inflight</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>unsigned int</code>
</li>
</ul>
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
unsigned int part_in_flight(struct request_queue * q, struct hd_struct * part)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
unsigned int part_in_flight(struct block_device * part)
```
</details>
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
