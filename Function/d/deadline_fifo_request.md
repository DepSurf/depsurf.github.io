# Function: <code>deadline_fifo_request</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583751088,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/deadline-iosched.c:248",
      "file": "block/deadline-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/deadline-iosched.c:deadline_dispatch_requests",
        "block/deadline-iosched.c:deadline_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583751088,
      "name": "deadline_fifo_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583859328,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:200",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859328,
      "name": "deadline_fifo_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584049968,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:201",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049968,
      "name": "deadline_fifo_request",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584172512,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:201",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172512,
      "name": "deadline_fifo_request",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584569376,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:201",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569376,
      "name": "deadline_fifo_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687648,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:201",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687648,
      "name": "deadline_fifo_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584715840,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:203",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715840,
      "name": "deadline_fifo_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585144069,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:296",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:__dd_dispatch_request"
      ],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585142880,
      "name": "deadline_fifo_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071592320926,
      "name": "deadline_fifo_request.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585876389,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:285",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:__dd_dispatch_request"
      ],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874672,
      "name": "deadline_fifo_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071594105480,
      "name": "deadline_fifo_request.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586661461,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:332",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:__dd_dispatch_request"
      ],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586659472,
      "name": "deadline_fifo_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071596109774,
      "name": "deadline_fifo_request.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586919536,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:346",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:__dd_dispatch_request"
      ],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586917808,
      "name": "deadline_fifo_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
    },
    {
      "addr": 18446744071596633714,
      "name": "deadline_fifo_request.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
struct request * deadline_fifo_request(struct deadline_data * dd, struct dd_per_prio * per_prio, enum dd_data_dir data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587197883,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:346",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:__dd_dispatch_request"
      ],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587196576,
      "name": "deadline_fifo_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
    },
    {
      "addr": 18446744071597540268,
      "name": "deadline_fifo_request.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071587197280,
      "name": "deadline_fifo_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071597540521,
      "name": "deadline_fifo_request.cold",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496028128,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:201",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496028128,
      "name": "deadline_fifo_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229368808,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:201",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229368808,
      "name": "deadline_fifo_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290261232,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:201",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290261232,
      "name": "deadline_fifo_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275117042,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:201",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275117042,
      "name": "deadline_fifo_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584141248,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:201",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584141248,
      "name": "deadline_fifo_request",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584076784,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:201",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076784,
      "name": "deadline_fifo_request",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584125008,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:201",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125008,
      "name": "deadline_fifo_request",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_fifo_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584229360,
      "name": "deadline_fifo_request",
      "external": false,
      "loc": "block/mq-deadline.c:201",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584229360,
      "name": "deadline_fifo_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
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
struct request * deadline_fifo_request(struct deadline_data * dd, int data_dir)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct request * deadline_fifo_request(struct deadline_data * dd, struct dd_per_prio * per_prio, enum dd_data_dir data_dir)
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
