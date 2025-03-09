# Function: <code>blk_trace_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580266128,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:310",
      "file": "kernel/trace/blktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:compat_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_shutdown"
      ],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266128,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580319337,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:316",
      "file": "kernel/trace/blktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:blk_trace_shutdown",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:compat_blk_trace_setup"
      ],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309360,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580365497,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:316",
      "file": "kernel/trace/blktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:blk_trace_shutdown",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:compat_blk_trace_setup"
      ],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580355536,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580377385,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:315",
      "file": "kernel/trace/blktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:blk_trace_shutdown",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:compat_blk_trace_setup"
      ],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367968,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580421728,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:369",
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
      "addr": 18446744071580421728,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483584,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:369",
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
      "addr": 18446744071580483584,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538896,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:357",
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
      "addr": 18446744071580538896,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580595536,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:357",
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
      "addr": 18446744071580595536,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580642640,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:358",
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
      "addr": 18446744071580642640,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580748384,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:361",
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
      "addr": 18446744071580748384,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580737152,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:361",
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
      "addr": 18446744071580737152,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580741920,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:360",
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
      "addr": 18446744071580741920,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926272,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:370",
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
      "addr": 18446744071580926272,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164608,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:370",
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
      "addr": 18446744071581164608,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581479088,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:402",
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
      "addr": 18446744071581479088,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581597024,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:402",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_release",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581597024,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581709456,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:402",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:disk_release",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581709456,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491949192,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:358",
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
      "addr": 18446603336491949192,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225885892,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:358",
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
      "addr": 3225885892,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285048704,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:358",
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
      "addr": 13835058055285048704,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272221758,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:358",
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
      "addr": 18446743936272221758,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580611440,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:358",
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
      "addr": 18446744071580611440,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557760,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:358",
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
      "addr": 18446744071580557760,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580602688,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:358",
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
      "addr": 18446744071580602688,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int blk_trace_remove(struct request_queue * q)
```

```json
{
  "name": "blk_trace_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580659728,
      "name": "blk_trace_remove",
      "external": true,
      "loc": "kernel/trace/blktrace.c:358",
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
      "addr": 18446744071580659728,
      "name": "blk_trace_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
