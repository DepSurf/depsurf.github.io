# Function: <code>iocg_unlock</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iocg_unlock(struct ioc_gq * iocg, bool unlock_ioc, long unsigned int * flags)
```

```json
{
  "name": "iocg_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584684801,
      "name": "iocg_unlock",
      "external": false,
      "loc": "block/blk-iocost.c:742",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584674800,
      "name": "iocg_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
  "name": "iocg_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584712314,
      "name": "iocg_unlock",
      "external": false,
      "loc": "block/blk-iocost.c:742",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
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
  "name": "iocg_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585136198,
      "name": "iocg_unlock",
      "external": false,
      "loc": "block/blk-iocost.c:742",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
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
  "name": "iocg_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585867347,
      "name": "iocg_unlock",
      "external": false,
      "loc": "block/blk-iocost.c:741",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
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
  "name": "iocg_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586651032,
      "name": "iocg_unlock",
      "external": false,
      "loc": "block/blk-iocost.c:738",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
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
  "name": "iocg_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586909776,
      "name": "iocg_unlock",
      "external": false,
      "loc": "block/blk-iocost.c:740",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
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
  "name": "iocg_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587187808,
      "name": "iocg_unlock",
      "external": false,
      "loc": "block/blk-iocost.c:740",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void iocg_unlock(struct ioc_gq * iocg, bool unlock_ioc, long unsigned int * flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void iocg_unlock(struct ioc_gq * iocg, bool unlock_ioc, long unsigned int * flags)
```
</details>
</li>
</ul>
