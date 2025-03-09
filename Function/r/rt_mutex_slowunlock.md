# Function: <code>rt_mutex_slowunlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587375248,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1263",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587375248,
      "name": "rt_mutex_slowunlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587876256,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1269",
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
      "addr": 18446744071587876256,
      "name": "rt_mutex_slowunlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093056,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1333",
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
      "addr": 18446744071588093056,
      "name": "rt_mutex_slowunlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588318800,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1345",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588318800,
      "name": "rt_mutex_slowunlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588884320,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1340",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588884320,
      "name": "rt_mutex_slowunlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589262656,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1339",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589262656,
      "name": "rt_mutex_slowunlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589505152,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1339",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505152,
      "name": "rt_mutex_slowunlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589967216,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1340",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589967216,
      "name": "rt_mutex_slowunlock",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590194880,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590194880,
      "name": "rt_mutex_slowunlock",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591210864,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1336",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591210864,
      "name": "rt_mutex_slowunlock",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591706112,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1336",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591706112,
      "name": "rt_mutex_slowunlock",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591648755,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1312",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
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
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592822252,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1279",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_unlock"
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
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594729768,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1291",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_unlock"
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
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596481512,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1329",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_unlock"
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
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597023048,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1387",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_unlock"
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
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597952392,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1406",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:rt_mutex_unlock"
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503940704,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503940704,
      "name": "rt_mutex_slowunlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236550104,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236550104,
      "name": "rt_mutex_slowunlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297793248,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297793248,
      "name": "rt_mutex_slowunlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279805872,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279805872,
      "name": "rt_mutex_slowunlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589797168,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589797168,
      "name": "rt_mutex_slowunlock",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589519616,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589519616,
      "name": "rt_mutex_slowunlock",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590240576,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590240576,
      "name": "rt_mutex_slowunlock",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
```

```json
{
  "name": "rt_mutex_slowunlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590290912,
      "name": "rt_mutex_slowunlock",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590290912,
      "name": "rt_mutex_slowunlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
bool rt_mutex_slowunlock(struct rt_mutex * lock, struct wake_q_head * wake_q)
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
