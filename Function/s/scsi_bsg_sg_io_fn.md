# Function: <code>scsi_bsg_sg_io_fn</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int scsi_bsg_sg_io_fn(struct request_queue * q, struct sg_io_v4 * hdr, fmode_t mode, unsigned int timeout)
```

```json
{
  "name": "scsi_bsg_sg_io_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_bsg_sg_io_fn",
      "external": false,
      "loc": "drivers/scsi/scsi_bsg.c:12",
      "file": "drivers/scsi/scsi_bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588023008,
      "name": "scsi_bsg_sg_io_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
    },
    {
      "addr": 18446744071592528933,
      "name": "scsi_bsg_sg_io_fn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int scsi_bsg_sg_io_fn(struct request_queue * q, struct sg_io_v4 * hdr, fmode_t mode, unsigned int timeout)
```

```json
{
  "name": "scsi_bsg_sg_io_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_bsg_sg_io_fn",
      "external": false,
      "loc": "drivers/scsi/scsi_bsg.c:12",
      "file": "drivers/scsi/scsi_bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589384688,
      "name": "scsi_bsg_sg_io_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    },
    {
      "addr": 18446744071594400352,
      "name": "scsi_bsg_sg_io_fn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
int scsi_bsg_sg_io_fn(struct request_queue * q, struct sg_io_v4 * hdr, fmode_t mode, unsigned int timeout)
```

```json
{
  "name": "scsi_bsg_sg_io_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_bsg_sg_io_fn",
      "external": false,
      "loc": "drivers/scsi/scsi_bsg.c:12",
      "file": "drivers/scsi/scsi_bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590957120,
      "name": "scsi_bsg_sg_io_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
    },
    {
      "addr": 18446744071596260386,
      "name": "scsi_bsg_sg_io_fn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int scsi_bsg_sg_io_fn(struct request_queue * q, struct sg_io_v4 * hdr, bool open_for_write, unsigned int timeout)
```

```json
{
  "name": "scsi_bsg_sg_io_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_bsg_sg_io_fn",
      "external": false,
      "loc": "drivers/scsi/scsi_bsg.c:12",
      "file": "drivers/scsi/scsi_bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591301200,
      "name": "scsi_bsg_sg_io_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
    },
    {
      "addr": 18446744071596788431,
      "name": "scsi_bsg_sg_io_fn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int scsi_bsg_sg_io_fn(struct request_queue * q, struct sg_io_v4 * hdr, bool open_for_write, unsigned int timeout)
```

```json
{
  "name": "scsi_bsg_sg_io_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_bsg_sg_io_fn",
      "external": false,
      "loc": "drivers/scsi/scsi_bsg.c:12",
      "file": "drivers/scsi/scsi_bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591649408,
      "name": "scsi_bsg_sg_io_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
    },
    {
      "addr": 18446744071597697407,
      "name": "scsi_bsg_sg_io_fn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int scsi_bsg_sg_io_fn(struct request_queue * q, struct sg_io_v4 * hdr, fmode_t mode, unsigned int timeout)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool open_for_write</code>
</li>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
