# Function: <code>sync_timeline_signal</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585318148,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:136",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585405654,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:136",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585835184,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:205",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585835184,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586082400,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:205",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586082400,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586226464,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:204",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586226464,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586470208,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:195",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586470208,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586618048,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618048,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587413136,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587413136,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587482880,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587482880,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587365152,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587365152,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587932128,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071592525185,
      "name": "sync_timeline_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283552,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071594396593,
      "name": "sync_timeline_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590845200,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071596259619,
      "name": "sync_timeline_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591188208,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071596787747,
      "name": "sync_timeline_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:230",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591534800,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071597696696,
      "name": "sync_timeline_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499507984,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499507984,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231977316,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231977316,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292796240,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292796240,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276719248,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276719248,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586308528,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586308528,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586149584,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586149584,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586566016,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586566016,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```

```json
{
  "name": "sync_timeline_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586677680,
      "name": "sync_timeline_signal",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:192",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586677680,
      "name": "sync_timeline_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void sync_timeline_signal(struct sync_timeline * obj, unsigned int inc)
```
</details>
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
