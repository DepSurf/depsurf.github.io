# Function: <code>rt_mutex_futex_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wqh)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587376656,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1497",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376656,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
bool rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wqh)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587877728,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1506",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877728,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
bool rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wqh)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094560,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1570",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094560,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588320320,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1616",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320320,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588885904,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1616",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588885904,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589264224,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1636",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589264224,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589506736,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1636",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589506736,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589968832,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1637",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589968832,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590196496,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1635",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590196496,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591212576,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1633",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591212576,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591707840,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1633",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591707840,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591654576,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1530",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591654576,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void rt_mutex_futex_unlock(struct rt_mutex_base * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592828096,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:166",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592828096,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void rt_mutex_futex_unlock(struct rt_mutex_base * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594736592,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:188",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594736592,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void rt_mutex_futex_unlock(struct rt_mutex_base * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596488464,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:188",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596488464,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void rt_mutex_futex_unlock(struct rt_mutex_base * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597029776,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:188",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597029776,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void rt_mutex_futex_unlock(struct rt_mutex_base * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597959168,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:188",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597959168,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503943152,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1635",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503943152,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236552080,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1635",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236552080,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297795808,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1635",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297795808,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279807308,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1635",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279807308,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589798784,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1635",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589798784,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589521232,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1635",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589521232,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590242192,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1635",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590242192,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void rt_mutex_futex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590292496,
      "name": "rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1635",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590292496,
      "name": "rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct wake_q_head * wqh</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
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
