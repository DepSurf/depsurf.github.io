# Function: <code>rt_mutex_slowlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587375888,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1170",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock",
        "kernel/locking/rtmutex.c:rt_mutex_timed_lock",
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_timed_futex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587375888,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587876960,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1166",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_timed_lock",
        "kernel/locking/rtmutex.c:rt_mutex_timed_futex_lock",
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587876960,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093760,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1230",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_timed_lock",
        "kernel/locking/rtmutex.c:rt_mutex_timed_futex_lock",
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093760,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588319504,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1243",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319504,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588885040,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1231",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588885040,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589263376,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1231",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589263376,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589505888,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1231",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505888,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589967952,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1232",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589967952,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590195616,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1230",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590195616,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591211616,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1228",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_timed_lock",
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591211616,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591706880,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1228",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_timed_lock",
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591706880,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591653552,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1193",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591653552,
      "name": "rt_mutex_slowlock.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592827360,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1621",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex_api.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592827360,
      "name": "rt_mutex_slowlock.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594736008,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1637",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_lock_killable",
        "kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex_api.c:rt_mutex_lock"
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
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596487800,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1675",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_lock_killable",
        "kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex_api.c:rt_mutex_lock"
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
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597029200,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1733",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_lock_killable",
        "kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex_api.c:rt_mutex_lock"
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
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597958560,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1752",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_lock_killable",
        "kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex_api.c:rt_mutex_lock"
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503941984,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1230",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_timed_lock",
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503941984,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236551084,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1230",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_timed_lock",
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236551084,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297794544,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1230",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_timed_lock",
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297794544,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279806556,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1230",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279806556,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589797904,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1230",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589797904,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589520352,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1230",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589520352,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590241312,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1230",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590241312,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
```

```json
{
  "name": "rt_mutex_slowlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590291664,
      "name": "rt_mutex_slowlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1230",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590291664,
      "name": "rt_mutex_slowlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int rt_mutex_slowlock(struct rt_mutex * lock, int state, struct hrtimer_sleeper * timeout, enum rtmutex_chainwalk chwalk)
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
