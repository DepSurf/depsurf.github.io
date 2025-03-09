# Function: <code>__blk_add_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int rw, u32 what, int error, int pdu_len, void * pdu_data)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270304,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:201",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270304,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580313552,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:203",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313552,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580360832,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:203",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360832,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580374144,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:205",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580374144,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580428560,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:225",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580428560,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1101
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580490384,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:225",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490384,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1055
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580545728,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:213",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545728,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1055
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580602320,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:213",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602320,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1119
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580649504,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:213",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649504,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1119
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, u64 cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580750624,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:215",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio_queue",
        "kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_backmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "kernel/trace/blktrace.c:blk_add_trace_bio_bounce",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580750624,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, u64 cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580739360,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:215",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580739360,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, u64 cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580745104,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:215",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745104,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 982
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, u64 cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:215",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_merge",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928080,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1042
    },
    {
      "addr": 18446744071592173847,
      "name": "__blk_add_trace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, u64 cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:215",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_getrq",
        "kernel/trace/blktrace.c:blk_add_trace_bio_queue",
        "kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_backmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_bounce",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165392,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1273
    },
    {
      "addr": 18446744071593947412,
      "name": "__blk_add_trace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, const blk_opf_t opf, u32 what, int error, int pdu_len, void * pdu_data, u64 cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:215",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_getrq",
        "kernel/trace/blktrace.c:blk_add_trace_bio_queue",
        "kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_backmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "kernel/trace/blktrace.c:blk_add_trace_bio_bounce",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479984,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1213
    },
    {
      "addr": 18446744071596007149,
      "name": "__blk_add_trace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, const blk_opf_t opf, u32 what, int error, int pdu_len, void * pdu_data, u64 cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:215",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_getrq",
        "kernel/trace/blktrace.c:blk_add_trace_bio_queue",
        "kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_backmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "kernel/trace/blktrace.c:blk_add_trace_bio_bounce",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581597920,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
    },
    {
      "addr": 18446744071596525964,
      "name": "__blk_add_trace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, const blk_opf_t opf, u32 what, int error, int pdu_len, void * pdu_data, u64 cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:215",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_getrq",
        "kernel/trace/blktrace.c:blk_add_trace_bio_queue",
        "kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_backmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "kernel/trace/blktrace.c:blk_add_trace_bio_bounce",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710352,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
    },
    {
      "addr": 18446744071597426574,
      "name": "__blk_add_trace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491954112,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:213",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491954112,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225889120,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:213",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225889120,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285058544,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:213",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285058544,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272228056,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:213",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272228056,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580618304,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:213",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580618304,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1119
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580564976,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:213",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580564976,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1102
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580609552,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:213",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609552,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1119
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
void __blk_add_trace(struct blk_trace * bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void * pdu_data, union kernfs_node_id * cgid)
```

```json
{
  "name": "__blk_add_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580666624,
      "name": "__blk_add_trace",
      "external": false,
      "loc": "kernel/trace/blktrace.c:213",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_driver_data",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_plug",
        "kernel/trace/blktrace.c:blk_add_trace_bio",
        "kernel/trace/blktrace.c:blk_add_trace_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580666624,
      "name": "__blk_add_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1155
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>bt, sector, bytes, rw, what, error, pdu_len, pdu_data</code> ➡️ <code>bt, sector, bytes, op, op_flags, what, error, pdu_len, pdu_data</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>union kernfs_node_id * cgid</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>union kernfs_node_id * cgid</code> ➡️ <code>u64 cgid</code>
</li>
</ul>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>bt, sector, bytes, op, op_flags, what, error, pdu_len, pdu_data, cgid</code> ➡️ <code>bt, sector, bytes, opf, what, error, pdu_len, pdu_data, cgid</code>
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
