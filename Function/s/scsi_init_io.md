# Function: <code>scsi_init_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584802416,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1113",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_setup_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same_cmnd",
        "drivers/scsi/sd.c:sd_setup_discard_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584802416,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585163488,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1027",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_setup_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585163488,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585357872,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1036",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_setup_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585357872,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585443952,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1032",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_setup_cmnd",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585443952,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585874880,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1061",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_setup_cmnd",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874880,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586120944,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1098",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_setup_cmnd",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586120944,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586266208,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1050",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586266208,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586505696,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1020",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586505696,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586653584,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1020",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653584,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587458432,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:978",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_prep_fn",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587458432,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499550936,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1020",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499550936,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232015244,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1020",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232015244,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292845408,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1020",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292845408,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276750864,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1020",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276750864,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586344064,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1020",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586344064,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586185392,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1020",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586185392,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586601552,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1020",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586601552,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_init_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586713824,
      "name": "scsi_init_io",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1020",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586713824,
      "name": "scsi_init_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
blk_status_t scsi_init_io(struct scsi_cmnd * cmd)
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
