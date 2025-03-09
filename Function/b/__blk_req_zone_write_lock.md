# Function: <code>__blk_req_zone_write_lock</code>

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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583793120,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:46",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/deadline-iosched.c:deadline_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583793120,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873744,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:49",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873744,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584065392,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:53",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584065392,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584188112,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:53",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188112,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584582224,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:99",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582224,
      "name": "__blk_req_zone_write_lock",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584699904,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:99",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584699904,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584727632,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:91",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584727632,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:91",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592321968,
      "name": "__blk_req_zone_write_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071585155216,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:90",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594106765,
      "name": "__blk_req_zone_write_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071585890336,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:87",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596110641,
      "name": "__blk_req_zone_write_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586678320,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:81",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596634951,
      "name": "__blk_req_zone_write_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586939248,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:81",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597542337,
      "name": "__blk_req_zone_write_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071587219968,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496054360,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:53",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496054360,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229382184,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:53",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229382184,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290287968,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:53",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290287968,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275130208,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:53",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275130208,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584156848,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:53",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156848,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584092112,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:53",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092112,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584140608,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:53",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140608,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __blk_req_zone_write_lock(struct request * rq)
```

```json
{
  "name": "__blk_req_zone_write_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584244768,
      "name": "__blk_req_zone_write_lock",
      "external": true,
      "loc": "block/blk-zoned.c:53",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244768,
      "name": "__blk_req_zone_write_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __blk_req_zone_write_lock(struct request * rq)
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
