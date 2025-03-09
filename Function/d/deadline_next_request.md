# Function: <code>deadline_next_request</code>

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
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583750560,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/deadline-iosched.c:279",
      "file": "block/deadline-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/deadline-iosched.c:deadline_dispatch_requests",
        "block/deadline-iosched.c:deadline_dispatch_requests",
        "block/deadline-iosched.c:deadline_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750560,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583858928,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:236",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858928,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049552,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:237",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049552,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584172096,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:237",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172096,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584570809,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:237",
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
      "addr": 18446744071584569056,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584689081,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:237",
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
      "addr": 18446744071584687312,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584717273,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:239",
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
      "addr": 18446744071584715184,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
struct request * deadline_next_request(struct deadline_data * dd, struct dd_per_prio * per_prio, enum dd_data_dir data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:330",
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
      "addr": 18446744071585142656,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071592320897,
      "name": "deadline_next_request.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct request * deadline_next_request(struct deadline_data * dd, struct dd_per_prio * per_prio, enum dd_data_dir data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:319",
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
      "addr": 18446744071585874032,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071594105451,
      "name": "deadline_next_request.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct request * deadline_next_request(struct deadline_data * dd, struct dd_per_prio * per_prio, enum dd_data_dir data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:371",
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
      "addr": 18446744071586659072,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071596109745,
      "name": "deadline_next_request.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct request * deadline_next_request(struct deadline_data * dd, struct dd_per_prio * per_prio, enum dd_data_dir data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:390",
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
      "addr": 18446744071586918480,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
    },
    {
      "addr": 18446744071596633817,
      "name": "deadline_next_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
struct request * deadline_next_request(struct deadline_data * dd, struct dd_per_prio * per_prio, enum dd_data_dir data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:390",
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
      "addr": 18446744071587195872,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
    },
    {
      "addr": 18446744071597540052,
      "name": "deadline_next_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496026768,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:237",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496026768,
      "name": "deadline_next_request",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229368300,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:237",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229368300,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290260608,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:237",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290260608,
      "name": "deadline_next_request",
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
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275116520,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:237",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275116520,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584140832,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:237",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140832,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584076368,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:237",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076368,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584124592,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:237",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124592,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
```

```json
{
  "name": "deadline_next_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228944,
      "name": "deadline_next_request",
      "external": false,
      "loc": "block/mq-deadline.c:237",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228944,
      "name": "deadline_next_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct request * deadline_next_request(struct deadline_data * dd, int data_dir)
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
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dd_per_prio * per_prio</code>
</li>
<li>
<b>Param reordered. </b>
<code>dd, data_dir</code> ➡️ <code>dd, per_prio, data_dir</code>
</li>
<li>
<b>Param type changed. </b>
<code>int data_dir</code> ➡️ <code>enum dd_data_dir data_dir</code>
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
