# Function: <code>rt_mutex_postunlock</code>

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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588320415,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1452",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720864,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588885999,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1447",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753568,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589264360,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1446",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787952,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589506872,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1446",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834416,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589968972,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1447",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869472,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590196636,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1445",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918096,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591212669,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1443",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:wake_futex_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963008,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591707933,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1443",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:wake_futex_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951152,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591654669,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1299",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591654320,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void rt_mutex_postunlock(struct rt_wake_q_head * wqh)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592828198,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:457",
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
      "addr": 18446744071592829040,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void rt_mutex_postunlock(struct rt_wake_q_head * wqh)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594736692,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:479",
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
      "addr": 18446744071594737712,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void rt_mutex_postunlock(struct rt_wake_q_head * wqh)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596488564,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:479",
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
      "addr": 18446744071596489712,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void rt_mutex_postunlock(struct rt_wake_q_head * wqh)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597029876,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:479",
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
      "addr": 18446744071597031024,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void rt_mutex_postunlock(struct rt_wake_q_head * wqh)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597959268,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:479",
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
      "addr": 18446744071597960416,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503943400,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1445",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491122928,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236552236,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1445",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225123336,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297796012,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1445",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284014144,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279807418,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1445",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271696626,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589798924,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1445",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890208,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589521372,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1445",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825168,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590242332,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1445",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878368,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_postunlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590292636,
      "name": "rt_mutex_postunlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1445",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923968,
      "name": "rt_mutex_postunlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void rt_mutex_postunlock(struct wake_q_head * wake_q)
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
