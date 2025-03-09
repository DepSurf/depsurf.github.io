# Function: <code>rt_mutex_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587376512,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1484",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:exit_pi_state_list",
        "drivers/i2c/i2c-core.c:i2c_unlock_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376512,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587877584,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1493",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:exit_pi_state_list",
        "drivers/i2c/i2c-core.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877584,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588094416,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1557",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:exit_pi_state_list",
        "drivers/i2c/i2c-core.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094416,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588318976,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1582",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588318976,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588884496,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1582",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588884496,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589262832,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1602",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589262832,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589505328,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1602",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505328,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589967408,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1603",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589967408,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590195072,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1601",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590195072,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591211056,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1599",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591211056,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591706304,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1599",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591706304,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591648640,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1477",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591648640,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592822144,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:116",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592822144,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594729648,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:138",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594729648,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596481392,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:138",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596481392,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597022928,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:138",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597022928,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597952272,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:138",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597952272,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503941120,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1601",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503941120,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236550284,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1601",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236550284,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297793568,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1601",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297793568,
      "name": "rt_mutex_unlock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279806044,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1601",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279806044,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589797360,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1601",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589797360,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589519808,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1601",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589519808,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590240768,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1601",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590240768,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void rt_mutex_unlock(struct rt_mutex * lock)
```

```json
{
  "name": "rt_mutex_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590291104,
      "name": "rt_mutex_unlock",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1601",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590291104,
      "name": "rt_mutex_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
