# Function: <code>elevator_init_mq</code>

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
int elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583552144,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:981",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583552144,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583673200,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:603",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673200,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861840,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:602",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861840,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:668",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965747,
      "name": "elevator_init_mq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583964560,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:668",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584354041,
      "name": "elevator_init_mq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584353216,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:661",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591372119,
      "name": "elevator_init_mq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584469824,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:662",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591314715,
      "name": "elevator_init_mq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584504768,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:675",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592312765,
      "name": "elevator_init_mq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584915344,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:679",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594095569,
      "name": "elevator_init_mq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585616736,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586385296,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:609",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586385296,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586631664,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:612",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586631664,
      "name": "elevator_init_mq",
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586902560,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:612",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586902560,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495787920,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:668",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495787920,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229138548,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:668",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229138548,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289966432,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:668",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289966432,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274930270,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:668",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274930270,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:668",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583934483,
      "name": "elevator_init_mq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583933296,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:668",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871427,
      "name": "elevator_init_mq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583870240,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:668",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918243,
      "name": "elevator_init_mq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583917056,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void elevator_init_mq(struct request_queue * q)
```

```json
{
  "name": "elevator_init_mq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elevator_init_mq",
      "external": true,
      "loc": "block/elevator.c:668",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:__device_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584019633,
      "name": "elevator_init_mq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584018432,
      "name": "elevator_init_mq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int elevator_init_mq(struct request_queue * q)
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
