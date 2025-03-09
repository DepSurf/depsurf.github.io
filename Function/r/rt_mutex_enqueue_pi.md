# Function: <code>rt_mutex_enqueue_pi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676016,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:219",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:remove_waiter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676016,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579695168,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:221",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695168,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722272,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:285",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722272,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717984,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:311",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717984,
      "name": "rt_mutex_enqueue_pi",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579750416,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:305",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750416,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579784864,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:305",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784864,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831344,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:305",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831344,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579865920,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:306",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865920,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914544,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:306",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914544,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959072,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:304",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959072,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947216,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:304",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947216,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591653116,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:302",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
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
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592825964,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:421",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
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
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594733794,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:423",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
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
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596485538,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:460",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
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
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597027079,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:485",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
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
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597956423,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:504",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491117992,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:306",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491117992,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225118972,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:306",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225118972,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284008560,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:306",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284008560,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271692834,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:306",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271692834,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886656,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:306",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886656,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821632,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:306",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821632,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874816,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:306",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874816,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "rt_mutex_enqueue_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920336,
      "name": "rt_mutex_enqueue_pi",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:306",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920336,
      "name": "rt_mutex_enqueue_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void rt_mutex_enqueue_pi(struct task_struct * task, struct rt_mutex_waiter * waiter)
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
