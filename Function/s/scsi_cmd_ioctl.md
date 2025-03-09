# Function: <code>scsi_cmd_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582827952,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:562",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582827952,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1052
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583107328,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:562",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583107328,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1058
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583218832,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:565",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583218832,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1058
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583316560,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:563",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583316560,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1073
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583499488,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:563",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583499488,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1073
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:559",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_blk_ioctl",
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583714193,
      "name": "scsi_cmd_ioctl.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071583713088,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1003
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:559",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_blk_ioctl",
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823441,
      "name": "scsi_cmd_ioctl.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071583822336,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1003
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:545",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_blk_ioctl",
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584013985,
      "name": "scsi_cmd_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584012880,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:545",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_blk_ioctl",
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584117521,
      "name": "scsi_cmd_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584116416,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:776",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515143,
      "name": "scsi_cmd_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071584513424,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:767",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591377635,
      "name": "scsi_cmd_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071584623344,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:763",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591319875,
      "name": "scsi_cmd_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071584651568,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495959048,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:545",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_blk_ioctl",
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495959048,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2660
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229304220,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:545",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_blk_ioctl",
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229304220,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1508
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290180512,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:545",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_blk_ioctl",
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290180512,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1992
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275065856,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:545",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_blk_ioctl",
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275065856,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 994
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:545",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_blk_ioctl",
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086257,
      "name": "scsi_cmd_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584085152,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:545",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_blk_ioctl",
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584022017,
      "name": "scsi_cmd_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584020912,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:545",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_blk_ioctl",
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070017,
      "name": "scsi_cmd_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584068912,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
```

```json
{
  "name": "scsi_cmd_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "scsi_cmd_ioctl",
      "external": true,
      "loc": "block/scsi_ioctl.c:545",
      "file": "block/scsi_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_blk_ioctl",
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172593,
      "name": "scsi_cmd_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584171488,
      "name": "scsi_cmd_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int scsi_cmd_ioctl(struct request_queue * q, struct gendisk * bd_disk, fmode_t mode, unsigned int cmd, void * arg)
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
