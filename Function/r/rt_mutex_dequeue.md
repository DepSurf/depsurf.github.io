# Function: <code>rt_mutex_dequeue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rt_mutex_dequeue(struct rt_mutex * lock, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675696,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:206",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:remove_waiter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675696,
      "name": "rt_mutex_dequeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void rt_mutex_dequeue(struct rt_mutex * lock, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579694848,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:208",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694848,
      "name": "rt_mutex_dequeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void rt_mutex_dequeue(struct rt_mutex * lock, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579721952,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:272",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721952,
      "name": "rt_mutex_dequeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void rt_mutex_dequeue(struct rt_mutex * lock, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717680,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:298",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717680,
      "name": "rt_mutex_dequeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579752963,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:295",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579787400,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:295",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579833864,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:295",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579868797,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:296",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579917421,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:296",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579962253,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:294",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579950397,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:294",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591652925,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:283",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592825773,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:402",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594733577,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:404",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596485321,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:441",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597026869,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:465",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597956213,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:484",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491121896,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:296",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225122552,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:296",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284013056,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:296",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271695900,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:296",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579889533,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:296",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579824493,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:296",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579877693,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:296",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_dequeue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579923325,
      "name": "rt_mutex_dequeue",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:296",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void rt_mutex_dequeue(struct rt_mutex * lock, struct rt_mutex_waiter * waiter)
```
</details>
</li>
</ul>
