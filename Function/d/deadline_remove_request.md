# Function: <code>deadline_remove_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582894607,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/deadline-iosched.c:116",
      "file": "block/deadline-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/deadline-iosched.c:deadline_dispatch_requests",
        "block/deadline-iosched.c:deadline_merged_requests"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583180352,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/deadline-iosched.c:115",
      "file": "block/deadline-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/deadline-iosched.c:deadline_dispatch_requests",
        "block/deadline-iosched.c:deadline_merged_requests"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583291258,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/deadline-iosched.c:115",
      "file": "block/deadline-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/deadline-iosched.c:deadline_dispatch_requests",
        "block/deadline-iosched.c:deadline_merged_requests"
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
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583353770,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/deadline-iosched.c:115",
      "file": "block/deadline-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/deadline-iosched.c:deadline_dispatch_requests",
        "block/deadline-iosched.c:deadline_merged_requests"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583535786,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/deadline-iosched.c:115",
      "file": "block/deadline-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/deadline-iosched.c:deadline_dispatch_requests",
        "block/deadline-iosched.c:deadline_merged_requests"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583751614,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/deadline-iosched.c:119",
      "file": "block/deadline-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/deadline-iosched.c:deadline_dispatch_requests",
        "block/deadline-iosched.c:deadline_merged_requests"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583857808,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:108",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583857808,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584048400,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:109",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584048400,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584170912,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:109",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584170912,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584567792,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:109",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584567792,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584686032,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:109",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584686032,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584714256,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:111",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714256,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void deadline_remove_request(struct request_queue * q, struct dd_per_prio * per_prio, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585140880,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:192",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585140880,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void deadline_remove_request(struct request_queue * q, struct dd_per_prio * per_prio, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585872016,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:169",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585872016,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void deadline_remove_request(struct request_queue * q, struct dd_per_prio * per_prio, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586656480,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:183",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586656480,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586919895,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:210",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587198177,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:210",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496025232,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:109",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496025232,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229366892,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:109",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229366892,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290258480,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:109",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290258480,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275115264,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:109",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275115264,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584139648,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:109",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139648,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584075184,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:109",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075184,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123408,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:109",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123408,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void deadline_remove_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "deadline_remove_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584227600,
      "name": "deadline_remove_request",
      "external": false,
      "loc": "block/mq-deadline.c:109",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584227600,
      "name": "deadline_remove_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void deadline_remove_request(struct request_queue * q, struct request * rq)
```
</details>
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
<code>q, rq</code> ➡️ <code>q, per_prio, rq</code>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void deadline_remove_request(struct request_queue * q, struct dd_per_prio * per_prio, struct request * rq)
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
