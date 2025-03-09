# Function: <code>blk_rq_map_user_io</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_rq_map_user_io(struct request * req, struct rq_map_data * map_data, void * ubuf, long unsigned int buf_len, gfp_t gfp_mask, bool vec, int iov_count, bool check_iter_count, int rw)
```

```json
{
  "name": "blk_rq_map_user_io",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586432720,
      "name": "blk_rq_map_user_io",
      "external": true,
      "loc": "block/blk-map.c:696",
      "file": "block/blk-map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/sg.c:sg_start_req",
        "drivers/scsi/sg.c:sg_start_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586432720,
      "name": "blk_rq_map_user_io.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071586433120,
      "name": "blk_rq_map_user_io",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_rq_map_user_io(struct request * req, struct rq_map_data * map_data, void * ubuf, long unsigned int buf_len, gfp_t gfp_mask, bool vec, int iov_count, bool check_iter_count, int rw)
```

```json
{
  "name": "blk_rq_map_user_io",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586679920,
      "name": "blk_rq_map_user_io",
      "external": true,
      "loc": "block/blk-map.c:694",
      "file": "block/blk-map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/sg.c:sg_start_req",
        "drivers/scsi/sg.c:sg_start_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586679920,
      "name": "blk_rq_map_user_io.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071586680320,
      "name": "blk_rq_map_user_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_rq_map_user_io(struct request * req, struct rq_map_data * map_data, void * ubuf, long unsigned int buf_len, gfp_t gfp_mask, bool vec, int iov_count, bool check_iter_count, int rw)
```

```json
{
  "name": "blk_rq_map_user_io",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586951232,
      "name": "blk_rq_map_user_io",
      "external": true,
      "loc": "block/blk-map.c:701",
      "file": "block/blk-map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/sg.c:sg_start_req",
        "drivers/scsi/sg.c:sg_start_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951232,
      "name": "blk_rq_map_user_io.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071586951632,
      "name": "blk_rq_map_user_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int blk_rq_map_user_io(struct request * req, struct rq_map_data * map_data, void * ubuf, long unsigned int buf_len, gfp_t gfp_mask, bool vec, int iov_count, bool check_iter_count, int rw)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
