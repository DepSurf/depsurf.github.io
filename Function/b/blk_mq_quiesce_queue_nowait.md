# Function: <code>blk_mq_quiesce_queue_nowait</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583231024,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:157",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583231024,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583408320,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:196",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408320,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583619845,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:211",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619808,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583724437,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:215",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724400,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583912757,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:218",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912720,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584015893,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:219",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584015856,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584408197,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:204",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:device_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408160,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584524053,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:208",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:device_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524016,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584556629,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:208",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:device_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556592,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584967813,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:215",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:device_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584967776,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585708892,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:244",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585671456,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586488892,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:244",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_quiesce_tagset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586447440,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586736447,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:203",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_quiesce_tagset"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_device_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586694448,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587008540,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:203",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_quiesce_tagset"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_device_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586965712,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495846092,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:219",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495846016,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229194196,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:219",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229194140,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290040352,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:219",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290040256,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274975828,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:219",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274975758,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583984629,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:219",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583984592,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583920485,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:219",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920448,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583968389,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:219",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968352,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue_nowait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584070405,
      "name": "blk_mq_quiesce_queue_nowait",
      "external": true,
      "loc": "block/blk-mq.c:219",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070368,
      "name": "blk_mq_quiesce_queue_nowait",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue * q)
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
