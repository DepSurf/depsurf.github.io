# Function: <code>__set_cyc2ns_scale</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604612525,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:122",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078208,
      "name": "__set_cyc2ns_scale.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579087536,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:123",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579087536,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579089504,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:123",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089504,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579101104,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:130",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:time_cpufreq_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579101104,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579101280,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:130",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:time_cpufreq_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579101280,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579107888,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:131",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:time_cpufreq_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579107888,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:131",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:time_cpufreq_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579133376,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071592057359,
      "name": "__set_cyc2ns_scale.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:131",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579170128,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071593825829,
      "name": "__set_cyc2ns_scale.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:131",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223776,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071595959597,
      "name": "__set_cyc2ns_scale.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:144",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226832,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071596476924,
      "name": "__set_cyc2ns_scale.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:144",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255696,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071597372709,
      "name": "__set_cyc2ns_scale.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579089856,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:123",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089856,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579022144,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:123",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579022144,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579089440,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:123",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089440,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```

```json
{
  "name": "__set_cyc2ns_scale",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579093712,
      "name": "__set_cyc2ns_scale",
      "external": false,
      "loc": "arch/x86/kernel/tsc.c:123",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579093712,
      "name": "__set_cyc2ns_scale",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now)
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
