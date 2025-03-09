# Function: <code>scsi_uninit_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584796940,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:615",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_unprep_fn",
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
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
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585157196,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:521",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_unprep_fn",
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
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
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585351468,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:530",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_unprep_fn",
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
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
void scsi_uninit_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585435664,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:559",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_unprep_fn",
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585435664,
      "name": "scsi_uninit_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void scsi_uninit_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585865984,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:584",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_unprep_fn",
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585865984,
      "name": "scsi_uninit_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void scsi_uninit_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586112528,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:597",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_unprep_fn",
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586112528,
      "name": "scsi_uninit_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586268626,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:547",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586512691,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:544",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586660643,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:544",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void scsi_uninit_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587447344,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:524",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447344,
      "name": "scsi_uninit_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void scsi_uninit_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587515328,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:509",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587515328,
      "name": "scsi_uninit_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void scsi_uninit_cmd(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587397040,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:476",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587397040,
      "name": "scsi_uninit_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587985743,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:481",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
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
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589342915,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:482",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
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
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590910485,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:478",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591253850,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:477",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591601070,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:475",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499560840,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:544",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232022424,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:544",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292855788,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:544",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276757560,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:544",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586351123,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:544",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586192451,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:544",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586608611,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:544",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_uninit_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586721027,
      "name": "scsi_uninit_cmd",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:544",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void scsi_uninit_cmd(struct scsi_cmnd * cmd)
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void scsi_uninit_cmd(struct scsi_cmnd * cmd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void scsi_uninit_cmd(struct scsi_cmnd * cmd)
```
</details>
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
void scsi_uninit_cmd(struct scsi_cmnd * cmd)
```
</details>
</li>
</ul>
