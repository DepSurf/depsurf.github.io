# Function: <code>rt_mutex_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587375488,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1470",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:fixup_owner",
        "kernel/futex.c:futex_lock_pi",
        "drivers/i2c/i2c-core.c:i2c_trylock_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587375488,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587876512,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1479",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:fixup_owner",
        "drivers/i2c/i2c-core.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587876512,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093296,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1543",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:fixup_owner",
        "drivers/i2c/i2c-core.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093296,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588319104,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1562",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319104,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588884624,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1562",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588884624,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589262960,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1582",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589262960,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589505456,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1582",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505456,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589967536,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1583",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589967536,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590195200,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1581",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590195200,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591211408,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1579",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591211408,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591706672,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1579",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591706672,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591649632,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1450",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591649632,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592823376,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:96",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592823376,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594730992,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:118",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594730992,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596482704,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:118",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596482704,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597023920,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:118",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597023920,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597953264,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:118",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597953264,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503941672,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1581",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503941672,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236550792,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1581",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236550792,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297794224,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1581",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297794224,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279806146,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1581",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279806146,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589797488,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1581",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589797488,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589519936,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1581",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589519936,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590240896,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1581",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590240896,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int rt_mutex_trylock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590291248,
      "name": "rt_mutex_trylock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1581",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590291248,
      "name": "rt_mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
