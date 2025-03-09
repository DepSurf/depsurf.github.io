# Function: <code>scsi_queue_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584809216,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:196",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_request_fn"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584809216,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585172024,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:162",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585170208,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585366824,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:160",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585365008,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585448310,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:213",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446464,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585879572,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:221",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585877760,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586125452,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:234",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586123616,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586268073,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:226",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586267856,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586512136,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:224",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586511920,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586660088,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:224",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586659872,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587460200,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:217",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587459984,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587528289,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:216",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587528096,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587409983,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:182",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_complete"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587409792,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587982105,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:184",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_complete"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587981872,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589338923,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_complete"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589338720,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590905307,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:183",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_complete"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590905088,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591249524,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:182",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_complete"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591249280,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591596772,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:182",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_complete"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596528,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499559964,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:224",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499559648,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232021904,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:224",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232021652,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292854876,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:224",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292854608,
      "name": "scsi_queue_insert",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276756364,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:224",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276756992,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586350568,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:224",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586350352,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586191896,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:224",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586191680,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586608056,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:224",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586607840,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void scsi_queue_insert(struct scsi_cmnd * cmd, int reason)
```

```json
{
  "name": "scsi_queue_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586720472,
      "name": "scsi_queue_insert",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:224",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done"
      ],
      "caller_func": [
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_error.c:scmd_eh_abort_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586720256,
      "name": "scsi_queue_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
