# Function: <code>put_sg_io_hdr</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int put_sg_io_hdr(const struct sg_io_hdr * hdr, void * argp)
```

```json
{
  "name": "put_sg_io_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584510576,
      "name": "put_sg_io_hdr",
      "external": true,
      "loc": "block/scsi_ioctl.c:558",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "drivers/scsi/sg.c:sg_new_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584510576,
      "name": "put_sg_io_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int put_sg_io_hdr(const struct sg_io_hdr * hdr, void * argp)
```

```json
{
  "name": "put_sg_io_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584620800,
      "name": "put_sg_io_hdr",
      "external": true,
      "loc": "block/scsi_ioctl.c:548",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "drivers/scsi/sg.c:sg_new_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584620800,
      "name": "put_sg_io_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int put_sg_io_hdr(const struct sg_io_hdr * hdr, void * argp)
```

```json
{
  "name": "put_sg_io_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584648752,
      "name": "put_sg_io_hdr",
      "external": true,
      "loc": "block/scsi_ioctl.c:544",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "drivers/scsi/sg.c:sg_new_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584648752,
      "name": "put_sg_io_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int put_sg_io_hdr(const struct sg_io_hdr * hdr, void * argp)
```

```json
{
  "name": "put_sg_io_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587948480,
      "name": "put_sg_io_hdr",
      "external": true,
      "loc": "drivers/scsi/scsi_ioctl.c:647",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sg.c:sg_new_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587948480,
      "name": "put_sg_io_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int put_sg_io_hdr(const struct sg_io_hdr * hdr, void * argp)
```

```json
{
  "name": "put_sg_io_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589303088,
      "name": "put_sg_io_hdr",
      "external": true,
      "loc": "drivers/scsi/scsi_ioctl.c:630",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sg.c:sg_new_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589303088,
      "name": "put_sg_io_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int put_sg_io_hdr(const struct sg_io_hdr * hdr, void * argp)
```

```json
{
  "name": "put_sg_io_hdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590868064,
      "name": "put_sg_io_hdr",
      "external": true,
      "loc": "drivers/scsi/scsi_ioctl.c:614",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sg.c:sg_new_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590868064,
      "name": "put_sg_io_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int put_sg_io_hdr(const struct sg_io_hdr * hdr, void * argp)
```

```json
{
  "name": "put_sg_io_hdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591211472,
      "name": "put_sg_io_hdr",
      "external": true,
      "loc": "drivers/scsi/scsi_ioctl.c:617",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sg.c:sg_new_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591211472,
      "name": "put_sg_io_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int put_sg_io_hdr(const struct sg_io_hdr * hdr, void * argp)
```

```json
{
  "name": "put_sg_io_hdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591558656,
      "name": "put_sg_io_hdr",
      "external": true,
      "loc": "drivers/scsi/scsi_ioctl.c:617",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/sg.c:sg_new_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591558656,
      "name": "put_sg_io_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int put_sg_io_hdr(const struct sg_io_hdr * hdr, void * argp)
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
