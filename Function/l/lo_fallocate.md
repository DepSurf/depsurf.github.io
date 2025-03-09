# Function: <code>lo_fallocate</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586371052,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:420",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587135088,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:432",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587135088,
      "name": "lo_fallocate.isra.0",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587220880,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:429",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587220880,
      "name": "lo_fallocate.isra.0",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587108896,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:471",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587108896,
      "name": "lo_fallocate.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587680192,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:461",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587680192,
      "name": "lo_fallocate.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589027664,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:309",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589027664,
      "name": "lo_fallocate.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590555872,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:309",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590555872,
      "name": "lo_fallocate.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590884304,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:309",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590884304,
      "name": "lo_fallocate.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591227840,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:305",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591227840,
      "name": "lo_fallocate.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499211444,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:420",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int lo_fallocate(struct loop_device * lo, struct request * rq, loff_t pos, int mode)
```

```json
{
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231734052,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:420",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231734052,
      "name": "lo_fallocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int lo_fallocate(struct loop_device * lo, struct request * rq, loff_t pos, int mode)
```

```json
{
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292406304,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:420",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292406304,
      "name": "lo_fallocate",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int lo_fallocate(struct loop_device * lo, struct request * rq, loff_t pos, int mode)
```

```json
{
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276493434,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:420",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276493434,
      "name": "lo_fallocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586132940,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:420",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
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
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585977548,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:420",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
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
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586319020,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:420",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
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
  "name": "lo_fallocate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586430572,
      "name": "lo_fallocate",
      "external": false,
      "loc": "drivers/block/loop.c:420",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int lo_fallocate(struct loop_device * lo, struct request * rq, loff_t pos, int mode)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int lo_fallocate(struct loop_device * lo, struct request * rq, loff_t pos, int mode)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int lo_fallocate(struct loop_device * lo, struct request * rq, loff_t pos, int mode)
```
</details>
</li>
</ul>
