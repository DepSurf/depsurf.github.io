# Function: <code>scsi_alloc_request</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct request * scsi_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "scsi_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589332817,
      "name": "scsi_alloc_request",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1128",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:__scsi_execute"
      ],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn",
        "drivers/scsi/sr.c:sr_read_cdda_bpc",
        "drivers/scsi/sg.c:sg_start_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589326688,
      "name": "scsi_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct request * scsi_alloc_request(struct request_queue * q, blk_opf_t opf, blk_mq_req_flags_t flags)
```

```json
{
  "name": "scsi_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590899073,
      "name": "scsi_alloc_request",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1133",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:__scsi_execute"
      ],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn",
        "drivers/scsi/sr.c:sr_read_cdda_bpc",
        "drivers/scsi/sg.c:sg_start_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590892880,
      "name": "scsi_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct request * scsi_alloc_request(struct request_queue * q, blk_opf_t opf, blk_mq_req_flags_t flags)
```

```json
{
  "name": "scsi_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591243075,
      "name": "scsi_alloc_request",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1134",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_execute_cmd"
      ],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn",
        "drivers/scsi/sr.c:sr_read_cdda_bpc",
        "drivers/scsi/sg.c:sg_start_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591236320,
      "name": "scsi_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct request * scsi_alloc_request(struct request_queue * q, blk_opf_t opf, blk_mq_req_flags_t flags)
```

```json
{
  "name": "scsi_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591590323,
      "name": "scsi_alloc_request",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1133",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_execute_cmd"
      ],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn",
        "drivers/scsi/sr.c:sr_read_cdda_bpc",
        "drivers/scsi/sg.c:sg_start_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591583568,
      "name": "scsi_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct request * scsi_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int op</code>
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
