# Function: <code>mark_wakeup_next_waiter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587375361,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:976",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587876390,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:974",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
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
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588093186,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1038",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718208,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1030",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718208,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579750608,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1018",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750608,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579785072,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1018",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785072,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831552,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1018",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831552,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866208,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1019",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866208,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914832,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1017",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914832,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959312,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1015",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959312,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947456,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1015",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947456,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591648384,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:989",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591648384,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void mark_wakeup_next_waiter(struct rt_wake_q_head * wqh, struct rt_mutex_base * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592821888,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1182",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex_api.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592821888,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void mark_wakeup_next_waiter(struct rt_wake_q_head * wqh, struct rt_mutex_base * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594729376,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1194",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex_api.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594729376,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void mark_wakeup_next_waiter(struct rt_wake_q_head * wqh, struct rt_mutex_base * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596481104,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1232",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex_api.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596481104,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void mark_wakeup_next_waiter(struct rt_wake_q_head * wqh, struct rt_mutex_base * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597022656,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1288",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex_api.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597022656,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct rt_wake_q_head * wqh, struct rt_mutex_base * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597952000,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1307",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex_api.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597952000,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491118328,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1017",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491118328,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225119496,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1017",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225119496,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284008912,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1017",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284008912,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271693114,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1017",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271693114,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886944,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1017",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886944,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821920,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1017",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821920,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579875104,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1017",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579875104,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```

```json
{
  "name": "mark_wakeup_next_waiter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920624,
      "name": "mark_wakeup_next_waiter",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1017",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920624,
      "name": "mark_wakeup_next_waiter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head * wake_q, struct rt_mutex * lock)
```
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rt_wake_q_head * wqh</code>
</li>
<li>
<b>Param removed. </b>
<code>struct wake_q_head * wake_q</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt_mutex * lock</code> ➡️ <code>struct rt_mutex_base * lock</code>
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
