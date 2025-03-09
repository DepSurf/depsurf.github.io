# Function: <code>scsi_free_sgtables</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_free_sgtables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587463438,
      "name": "scsi_free_sgtables",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:534",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_prep_fn",
        "drivers/scsi/scsi_lib.c:scsi_init_io",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_free_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587531344,
      "name": "scsi_free_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:519",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587517504,
      "name": "scsi_free_sgtables",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_free_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587413352,
      "name": "scsi_free_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:486",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399104,
      "name": "scsi_free_sgtables",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_free_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587985706,
      "name": "scsi_free_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:491",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587970816,
      "name": "scsi_free_sgtables",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_free_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589342878,
      "name": "scsi_free_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:492",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589326576,
      "name": "scsi_free_sgtables",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_free_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590910448,
      "name": "scsi_free_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:488",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590892752,
      "name": "scsi_free_sgtables",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_free_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591253813,
      "name": "scsi_free_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:487",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591236192,
      "name": "scsi_free_sgtables",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_free_sgtables",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591601033,
      "name": "scsi_free_sgtables",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:485",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/scsi/sr.c:sr_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591583440,
      "name": "scsi_free_sgtables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void scsi_free_sgtables(struct scsi_cmnd * cmd)
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
