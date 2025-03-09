# Function: <code>bsg_register_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, void (*)(struct device *) release)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582864592,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:974",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582864592,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, void (*)(struct device *) release)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583150480,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:974",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583150480,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, void (*)(struct device *) release)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583262416,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:977",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262416,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, void (*)(struct device *) release)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583317808,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:976",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583317808,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, void (*)(struct device *) release)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583501472,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:967",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583501472,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583716232,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:900",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715840,
      "name": "bsg_register_queue.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071583720247,
      "name": "bsg_register_queue.part.16.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583720208,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:467",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826742,
      "name": "bsg_register_queue.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583826240,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:406",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017050,
      "name": "bsg_register_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584016544,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:406",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120570,
      "name": "bsg_register_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584120064,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:407",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584518458,
      "name": "bsg_register_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584517952,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:409",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591377749,
      "name": "bsg_register_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584626800,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:409",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591319989,
      "name": "bsg_register_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584654976,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
struct bsg_device * bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, bsg_sg_io_fn * sg_io_fn)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:185",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_register_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592319979,
      "name": "bsg_register_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585067792,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
struct bsg_device * bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, bsg_sg_io_fn * sg_io_fn)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:185",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_register_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594104507,
      "name": "bsg_register_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585792704,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bsg_device * bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, bsg_sg_io_fn * sg_io_fn)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586573712,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:187",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_register_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573712,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bsg_device * bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, bsg_sg_io_fn * sg_io_fn)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586831504,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:189",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_register_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586831504,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bsg_device * bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, bsg_sg_io_fn * sg_io_fn)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587108576,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:189",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_register_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587108576,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495966376,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:406",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495966376,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229308780,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:406",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229308780,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290186736,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:406",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290186736,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275069016,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:406",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275069016,
      "name": "bsg_register_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446743936275069696,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:406",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584089306,
      "name": "bsg_register_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584088800,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:406",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025066,
      "name": "bsg_register_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584024560,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:406",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073066,
      "name": "bsg_register_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584072560,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int bsg_register_queue(struct request_queue * q, struct device * parent, const char * name, const struct bsg_ops * ops)
```

```json
{
  "name": "bsg_register_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_register_queue",
      "external": true,
      "loc": "block/bsg.c:406",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584175642,
      "name": "bsg_register_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584175136,
      "name": "bsg_register_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bsg_ops * ops</code>
</li>
<li>
<b>Param removed. </b>
<code>void (*)(struct device *) release</code>
</li>
</ul>
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
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bsg_sg_io_fn * sg_io_fn</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct bsg_ops * ops</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct bsg_device *</code>
</li>
</ul>
</details>
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
