# Function: <code>__blk_req_zone_write_unlock</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583793024,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:57",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__blk_put_request",
        "block/deadline-iosched.c:deadline_completed_request",
        "block/deadline-iosched.c:deadline_add_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583793024,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583874864,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:60",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874864,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584065488,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:64",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584065488,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584188208,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:64",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188208,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584582336,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:110",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests",
        "drivers/scsi/sd_zbc.c:sd_zbc_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582336,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584700000,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:110",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests",
        "drivers/scsi/sd_zbc.c:sd_zbc_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584700000,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584727728,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:102",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests",
        "drivers/scsi/sd_zbc.c:sd_zbc_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584727728,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:102",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_request",
        "drivers/scsi/sd_zbc.c:sd_zbc_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592322175,
      "name": "__blk_req_zone_write_unlock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071585155712,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:101",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "drivers/scsi/sd_zbc.c:sd_zbc_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594106940,
      "name": "__blk_req_zone_write_unlock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071585890880,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:98",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "drivers/scsi/sd_zbc.c:sd_zbc_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596110678,
      "name": "__blk_req_zone_write_unlock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586678512,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:92",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "drivers/scsi/sd_zbc.c:sd_zbc_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596635035,
      "name": "__blk_req_zone_write_unlock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586939600,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:92",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "drivers/scsi/sd_zbc.c:sd_zbc_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597542788,
      "name": "__blk_req_zone_write_unlock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071587220880,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496054600,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:64",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496054600,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229382428,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:64",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229382428,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290288144,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:64",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290288144,
      "name": "__blk_req_zone_write_unlock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275130578,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:64",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275130578,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584156944,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:64",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156944,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584092208,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:64",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092208,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584140704,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:64",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140704,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void __blk_req_zone_write_unlock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584244864,
      "name": "__blk_req_zone_write_unlock",
      "external": true,
      "loc": "block/blk-zoned.c:64",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244864,
      "name": "__blk_req_zone_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __blk_req_zone_write_unlock(struct request * rq)
```
</details>
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
