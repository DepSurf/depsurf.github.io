# Function: <code>blk_req_needs_zone_write_lock</code>

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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583792912,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:27",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/deadline-iosched.c:deadline_dispatch_requests",
        "block/deadline-iosched.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583792912,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873552,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:30",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873552,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584064336,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:34",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584064336,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584186464,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:34",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186464,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581984,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:66",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:deadline_fifo_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581984,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584698784,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:66",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:deadline_fifo_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698784,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584726880,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:58",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:deadline_fifo_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584726880,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:58",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592321862,
      "name": "blk_req_needs_zone_write_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071585154016,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:58",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594106553,
      "name": "blk_req_needs_zone_write_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071585888976,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:58",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596110369,
      "name": "blk_req_needs_zone_write_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586675904,
      "name": "blk_req_needs_zone_write_lock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:58",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596634750,
      "name": "blk_req_needs_zone_write_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586936928,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:58",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597541946,
      "name": "blk_req_needs_zone_write_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071587217584,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496051928,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:34",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496051928,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229381108,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:34",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229381108,
      "name": "blk_req_needs_zone_write_lock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290286624,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:34",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290286624,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275129246,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:34",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275129246,
      "name": "blk_req_needs_zone_write_lock",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584155200,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:34",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584155200,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090464,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:34",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090464,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584138960,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:34",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138960,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool blk_req_needs_zone_write_lock(struct request * rq)
```

```json
{
  "name": "blk_req_needs_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584243120,
      "name": "blk_req_needs_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:34",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243120,
      "name": "blk_req_needs_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool blk_req_needs_zone_write_lock(struct request * rq)
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
