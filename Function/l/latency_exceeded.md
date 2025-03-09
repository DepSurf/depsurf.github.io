# Function: <code>latency_exceeded</code>

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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583343329,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:332",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583400811,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:280",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583580363,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:279",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583797755,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:308",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583880379,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:233",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584071825,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:234",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584194593,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:234",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
int latency_exceeded(struct rq_wb * rwb, struct blk_rq_stat * stat)
```

```json
{
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584589584,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:234",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584589584,
      "name": "latency_exceeded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
int latency_exceeded(struct rq_wb * rwb, struct blk_rq_stat * stat)
```

```json
{
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584707248,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:234",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wb_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584707248,
      "name": "latency_exceeded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584736731,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:235",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585164557,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:235",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585900571,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:235",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586688507,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:236",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586949508,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:304",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587229940,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:303",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496062000,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:234",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229389576,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:234",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290297972,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:234",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275135706,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:234",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584163329,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:234",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584098593,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:234",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584147089,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:234",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
  "name": "latency_exceeded",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584251377,
      "name": "latency_exceeded",
      "external": false,
      "loc": "block/blk-wbt.c:234",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn"
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
int latency_exceeded(struct rq_wb * rwb, struct blk_rq_stat * stat)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int latency_exceeded(struct rq_wb * rwb, struct blk_rq_stat * stat)
```
</details>
</li>
</ul>
