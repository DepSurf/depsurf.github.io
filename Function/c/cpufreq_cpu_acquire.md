# Function: <code>cpufreq_cpu_acquire</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587827504,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:272",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587827504,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588032512,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:275",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588032512,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588893696,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:280",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893696,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588907989,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:280",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588905712,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588793824,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:277",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588793824,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589486112,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:277",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589486112,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590967184,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:278",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590967184,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592674549,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:278",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592671184,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593105301,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:283",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593102000,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593858053,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:284",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593854768,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501299384,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:275",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501299384,
      "name": "cpufreq_cpu_acquire",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233787816,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:275",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233787816,
      "name": "cpufreq_cpu_acquire",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294829376,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:275",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294829376,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587657504,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:275",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587657504,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587431376,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:275",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587431376,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587988656,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:275",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988656,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_acquire",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588104048,
      "name": "cpufreq_cpu_acquire",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:275",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588104048,
      "name": "cpufreq_cpu_acquire",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cpufreq_policy * cpufreq_cpu_acquire(unsigned int cpu)
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
