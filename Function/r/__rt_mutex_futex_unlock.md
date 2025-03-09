# Function: <code>__rt_mutex_futex_unlock</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588320375,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1593",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320272,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588885959,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1593",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588885856,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589264288,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1613",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589264176,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589506800,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1613",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589506688,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589968893,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1614",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589968784,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590196557,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1612",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590196448,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591212637,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1610",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:wake_futex_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591212528,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591707901,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1610",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:wake_futex_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591707792,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591654637,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1507",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591654528,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex_base * lock, struct rt_wake_q_head * wqh)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592828166,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:143",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592828048,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex_base * lock, struct rt_wake_q_head * wqh)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594736661,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:165",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594736512,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool __rt_mutex_futex_unlock(struct rt_mutex_base * lock, struct rt_wake_q_head * wqh)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596488533,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:165",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596488368,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool __rt_mutex_futex_unlock(struct rt_mutex_base * lock, struct rt_wake_q_head * wqh)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597029845,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:165",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597029680,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool __rt_mutex_futex_unlock(struct rt_mutex_base * lock, struct rt_wake_q_head * wqh)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597959237,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:165",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597959072,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503943260,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1612",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503943072,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236552160,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1612",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236552012,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297795896,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1612",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297795712,
      "name": "__rt_mutex_futex_unlock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279807358,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1612",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279807234,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589798845,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1612",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589798736,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589521293,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1612",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589521184,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590242253,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1612",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590242144,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rt_mutex_futex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590292557,
      "name": "__rt_mutex_futex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1612",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590292448,
      "name": "__rt_mutex_futex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool __rt_mutex_futex_unlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
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
