# Function: <code>__cfq_slice_expired</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __cfq_slice_expired(struct cfq_data * cfqd, struct cfq_queue * cfqq, bool timed_out)
```

```json
{
  "name": "__cfq_slice_expired",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582915680,
      "name": "__cfq_slice_expired",
      "external": false,
      "loc": "block/cfq-iosched.c:2640",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_preempt_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_completed_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915680,
      "name": "__cfq_slice_expired",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1405
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __cfq_slice_expired(struct cfq_data * cfqd, struct cfq_queue * cfqq, bool timed_out)
```

```json
{
  "name": "__cfq_slice_expired",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583202960,
      "name": "__cfq_slice_expired",
      "external": false,
      "loc": "block/cfq-iosched.c:2671",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_preempt_queue",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202960,
      "name": "__cfq_slice_expired",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1408
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __cfq_slice_expired(struct cfq_data * cfqd, struct cfq_queue * cfqq, bool timed_out)
```

```json
{
  "name": "__cfq_slice_expired",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583303232,
      "name": "__cfq_slice_expired",
      "external": false,
      "loc": "block/cfq-iosched.c:2663",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_preempt_queue",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583303232,
      "name": "__cfq_slice_expired",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __cfq_slice_expired(struct cfq_data * cfqd, struct cfq_queue * cfqq, bool timed_out)
```

```json
{
  "name": "__cfq_slice_expired",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583365552,
      "name": "__cfq_slice_expired",
      "external": false,
      "loc": "block/cfq-iosched.c:2668",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_preempt_queue",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365552,
      "name": "__cfq_slice_expired",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 939
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __cfq_slice_expired(struct cfq_data * cfqd, struct cfq_queue * cfqq, bool timed_out)
```

```json
{
  "name": "__cfq_slice_expired",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583552672,
      "name": "__cfq_slice_expired",
      "external": false,
      "loc": "block/cfq-iosched.c:2644",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583552672,
      "name": "__cfq_slice_expired",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __cfq_slice_expired(struct cfq_data * cfqd, struct cfq_queue * cfqq, bool timed_out)
```

```json
{
  "name": "__cfq_slice_expired",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583767424,
      "name": "__cfq_slice_expired",
      "external": false,
      "loc": "block/cfq-iosched.c:2647",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583767424,
      "name": "__cfq_slice_expired",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1487
    }
  ]
}
```
</details>
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void __cfq_slice_expired(struct cfq_data * cfqd, struct cfq_queue * cfqq, bool timed_out)
```
</details>
</li>
</ul>
