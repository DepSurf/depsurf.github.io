# Function: <code>__rt_mutex_futex_trylock</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588885792,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1515",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588885792,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589264112,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1535",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589264112,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589506624,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1535",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589506624,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589968720,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1536",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589968720,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590196384,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1534",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590196384,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591212448,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1532",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591212448,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591707712,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1532",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591707712,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591654464,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1495",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591654464,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int __rt_mutex_futex_trylock(struct rt_mutex_base * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592827984,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:131",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592827984,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int __rt_mutex_futex_trylock(struct rt_mutex_base * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594736432,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:153",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594736432,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int __rt_mutex_futex_trylock(struct rt_mutex_base * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596488272,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:153",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596488272,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int __rt_mutex_futex_trylock(struct rt_mutex_base * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597029584,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:153",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597029584,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int __rt_mutex_futex_trylock(struct rt_mutex_base * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597958976,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:153",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597958976,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503942992,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1534",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503942992,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236551932,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1534",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236551932,
      "name": "__rt_mutex_futex_trylock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297795600,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1534",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297795600,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279807166,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1534",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279807166,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589798672,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1534",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589798672,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589521120,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1534",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589521120,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590242080,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1534",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590242080,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "__rt_mutex_futex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590292384,
      "name": "__rt_mutex_futex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1534",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590292384,
      "name": "__rt_mutex_futex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __rt_mutex_futex_trylock(struct rt_mutex * lock)
```
</details>
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
