# Function: <code>bsg_scsi_fill_hdr</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583717088,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:143",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583717088,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583826048,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:72",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826048,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016320,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071584017021,
      "name": "bsg_scsi_fill_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584119840,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071584120541,
      "name": "bsg_scsi_fill_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584517728,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071584518429,
      "name": "bsg_scsi_fill_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626576,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071591377720,
      "name": "bsg_scsi_fill_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584654752,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071591319960,
      "name": "bsg_scsi_fill_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
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
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495964176,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495964176,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229308428,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229308428,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290185664,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290185664,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275069476,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275069476,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584088576,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071584089277,
      "name": "bsg_scsi_fill_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024336,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071584025037,
      "name": "bsg_scsi_fill_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072336,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071584073037,
      "name": "bsg_scsi_fill_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
```

```json
{
  "name": "bsg_scsi_fill_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_scsi_fill_hdr",
      "external": false,
      "loc": "block/bsg.c:65",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174912,
      "name": "bsg_scsi_fill_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071584175613,
      "name": "bsg_scsi_fill_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int bsg_scsi_fill_hdr(struct request * rq, struct sg_io_v4 * hdr, fmode_t mode)
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
