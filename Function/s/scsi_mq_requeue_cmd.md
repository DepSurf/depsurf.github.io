# Function: <code>scsi_mq_requeue_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584808994,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:120",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
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
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585172538,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:86",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert"
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
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585367337,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:86",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert"
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
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585449528,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:139",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585877344,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:141",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585877344,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586126809,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:142",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586269120,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:142",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586269120,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586513120,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:155",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513120,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586661072,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:155",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586661072,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587457504,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:155",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587457504,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587525808,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:154",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587525808,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587407472,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:120",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587407472,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587983836,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:120",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
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
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589341338,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:121",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590908078,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:114",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd, long unsigned int msecs)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591246848,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:114",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591246848,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd, long unsigned int msecs)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591594112,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:114",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591594112,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499561352,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:155",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499561352,
      "name": "scsi_mq_requeue_cmd",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232022928,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:155",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232022928,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292856400,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:155",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292856400,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276757974,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:155",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276757974,
      "name": "scsi_mq_requeue_cmd",
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586351552,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:155",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586351552,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586192880,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:155",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586192880,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586609040,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:155",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586609040,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_mq_requeue_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721488,
      "name": "scsi_mq_requeue_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:155",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721488,
      "name": "scsi_mq_requeue_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void scsi_mq_requeue_cmd(struct scsi_cmnd * cmd, long unsigned int msecs)
```
</details>
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
