# Function: <code>hv_stimer_cleanup</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588006192,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:135",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588006192,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588213808,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:136",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588213808,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589081728,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:141",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589081728,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589082736,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:141",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589082736,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588968896,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:154",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588968896,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:154",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592676612,
      "name": "hv_stimer_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589678752,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:154",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594561857,
      "name": "hv_stimer_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591183968,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:155",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596318679,
      "name": "hv_stimer_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592910480,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:155",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596848309,
      "name": "hv_stimer_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593349824,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:155",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597773234,
      "name": "hv_stimer_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594103824,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587825664,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:136",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587825664,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587535792,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:136",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hv/vmbus_drv.c:hv_crash_handler",
        "drivers/hv/hv.c:hv_synic_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587535792,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588168288,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:136",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588168288,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void hv_stimer_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588286144,
      "name": "hv_stimer_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:136",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588286144,
      "name": "hv_stimer_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void hv_stimer_cleanup(unsigned int cpu)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void hv_stimer_cleanup(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void hv_stimer_cleanup(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void hv_stimer_cleanup(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void hv_stimer_cleanup(unsigned int cpu)
```
</details>
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
