# Function: <code>__dd_dispatch_request</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583859876,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:270",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_dispatch_request"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584050596,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:271",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_dispatch_request"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584172977,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:271",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_dispatch_request"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct request * __dd_dispatch_request(struct deadline_data * dd)
```

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584570400,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:271",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570400,
      "name": "__dd_dispatch_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
struct request * __dd_dispatch_request(struct deadline_data * dd)
```

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584688672,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:271",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584688672,
      "name": "__dd_dispatch_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
struct request * __dd_dispatch_request(struct deadline_data * dd)
```

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584716864,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:273",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584716864,
      "name": "__dd_dispatch_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
struct request * __dd_dispatch_request(struct deadline_data * dd, struct dd_per_prio * per_prio)
```

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585143840,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:362",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585143840,
      "name": "__dd_dispatch_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
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
struct request * __dd_dispatch_request(struct deadline_data * dd, struct dd_per_prio * per_prio, long unsigned int latest_start)
```

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585876080,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:365",
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
      "addr": 18446744071585876080,
      "name": "__dd_dispatch_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
struct request * __dd_dispatch_request(struct deadline_data * dd, struct dd_per_prio * per_prio, long unsigned int latest_start)
```

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586661152,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:423",
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
      "addr": 18446744071586661152,
      "name": "__dd_dispatch_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
struct request * __dd_dispatch_request(struct deadline_data * dd, struct dd_per_prio * per_prio, long unsigned int latest_start)
```

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919184,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:443",
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
      "addr": 18446744071586919184,
      "name": "__dd_dispatch_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
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
struct request * __dd_dispatch_request(struct deadline_data * dd, struct dd_per_prio * per_prio, long unsigned int latest_start)
```

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:443",
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
      "addr": 18446744071587197536,
      "name": "__dd_dispatch_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 18446744071597540550,
      "name": "__dd_dispatch_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496028644,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:271",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_dispatch_request"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229369160,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:271",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_dispatch_request"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290261724,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:271",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_dispatch_request"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275117632,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:271",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_dispatch_request"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584141713,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:271",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_dispatch_request"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584077249,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:271",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_dispatch_request"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584125473,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:271",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_dispatch_request"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dd_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584229681,
      "name": "__dd_dispatch_request",
      "external": false,
      "loc": "block/mq-deadline.c:271",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_dispatch_request"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct request * __dd_dispatch_request(struct deadline_data * dd)
```
</details>
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
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int latest_start</code>
</li>
</ul>
</details>
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
