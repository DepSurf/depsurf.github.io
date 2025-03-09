# Function: <code>elv_rqhash_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582727104,
      "name": "elv_rqhash_add",
      "external": false,
      "loc": "block/elevator.c:257",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_rqhash_reposition",
        "block/elevator.c:__elv_add_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582727104,
      "name": "elv_rqhash_add.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583004624,
      "name": "elv_rqhash_add",
      "external": false,
      "loc": "block/elevator.c:257",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/elevator.c:elv_rqhash_reposition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004624,
      "name": "elv_rqhash_add.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583109856,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:257",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/elevator.c:elv_rqhash_reposition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583109856,
      "name": "elv_rqhash_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583164848,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:282",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/elevator.c:elv_rqhash_reposition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164848,
      "name": "elv_rqhash_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583339648,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:299",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/elevator.c:elv_rqhash_reposition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583339648,
      "name": "elv_rqhash_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583547600,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:268",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/elevator.c:elv_rqhash_reposition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583547600,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583670592,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:203",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_rqhash_reposition",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670592,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583859216,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:204",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_rqhash_reposition",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859216,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583961856,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:214",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_rqhash_reposition",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961856,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584349520,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:214",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_merged_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584349520,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584466160,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:213",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_merged_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584466160,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584501136,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:213",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_merged_request",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584501136,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584911632,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:213",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_merged_request",
        "block/mq-deadline.c:dd_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584911632,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585612544,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:218",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_merged_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585612544,
      "name": "elv_rqhash_add",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586381792,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:186",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_merged_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586381792,
      "name": "elv_rqhash_add",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586628112,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:186",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_merged_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586628112,
      "name": "elv_rqhash_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586898944,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:186",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_merged_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898944,
      "name": "elv_rqhash_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495784568,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:214",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_rqhash_reposition",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495784568,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229135716,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:214",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_rqhash_reposition",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229135716,
      "name": "elv_rqhash_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289960592,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:214",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_rqhash_reposition",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289960592,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274927292,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:214",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_rqhash_reposition",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274927292,
      "name": "elv_rqhash_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583930592,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:214",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_rqhash_reposition",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930592,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583867536,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:214",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_rqhash_reposition",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583867536,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583914352,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:214",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_rqhash_reposition",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583914352,
      "name": "elv_rqhash_add",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584015760,
      "name": "elv_rqhash_add",
      "external": true,
      "loc": "block/elevator.c:214",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_rqhash_reposition",
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584015760,
      "name": "elv_rqhash_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void elv_rqhash_add(struct request_queue * q, struct request * rq)
```
</details>
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
