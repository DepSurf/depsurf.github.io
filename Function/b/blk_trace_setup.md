# Function: <code>blk_trace_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580269856,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:534",
      "file": "kernel/trace/blktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269856,
      "name": "blk_trace_setup.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071580275104,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580313104,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:534",
      "file": "kernel/trace/blktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313104,
      "name": "blk_trace_setup.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071580318496,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580359280,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:534",
      "file": "kernel/trace/blktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359280,
      "name": "blk_trace_setup.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071580364656,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580371184,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:529",
      "file": "kernel/trace/blktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371184,
      "name": "blk_trace_setup.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071580372128,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580426464,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:600",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580426464,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580488288,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:600",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580488288,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580540928,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:588",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540928,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580597488,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:582",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597488,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580644688,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:583",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644688,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580748640,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:612",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748640,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580737408,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:603",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737408,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580743024,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:600",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580743024,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580927104,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:610",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927104,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581171200,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:610",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171200,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581478960,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:642",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581478960,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581596896,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:642",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596896,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581709328,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:642",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581709328,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491954000,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:583",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491954000,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225887052,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:583",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225887052,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285057232,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:583",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285057232,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272223936,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:583",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272223936,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580613488,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:583",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580613488,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580559808,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:583",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559808,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580604736,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:583",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604736,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int blk_trace_setup(struct request_queue * q, char * name, dev_t dev, struct block_device * bdev, char * arg)
```

```json
{
  "name": "blk_trace_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580661776,
      "name": "blk_trace_setup",
      "external": true,
      "loc": "kernel/trace/blktrace.c:583",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661776,
      "name": "blk_trace_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
