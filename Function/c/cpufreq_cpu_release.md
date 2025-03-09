# Function: <code>cpufreq_cpu_release</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:248",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587833200,
      "name": "cpufreq_cpu_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071587827440,
      "name": "cpufreq_cpu_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588032464,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:251",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588032464,
      "name": "cpufreq_cpu_release",
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
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588896071,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:256",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893632,
      "name": "cpufreq_cpu_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588908023,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:256",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588905648,
      "name": "cpufreq_cpu_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588796011,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:253",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588793760,
      "name": "cpufreq_cpu_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589488376,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:253",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589486048,
      "name": "cpufreq_cpu_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590970278,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:254",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590967120,
      "name": "cpufreq_cpu_release",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592674583,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:254",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
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
      "addr": 18446744071592671104,
      "name": "cpufreq_cpu_release",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593105406,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:259",
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
      "addr": 18446744071593101920,
      "name": "cpufreq_cpu_release",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593858158,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:260",
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
      "addr": 18446744071593854688,
      "name": "cpufreq_cpu_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501299312,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:251",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501299312,
      "name": "cpufreq_cpu_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233787740,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:251",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233787740,
      "name": "cpufreq_cpu_release",
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
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294829264,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:251",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294829264,
      "name": "cpufreq_cpu_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587657456,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:251",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587657456,
      "name": "cpufreq_cpu_release",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587431328,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:251",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587431328,
      "name": "cpufreq_cpu_release",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587988608,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:251",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988608,
      "name": "cpufreq_cpu_release",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_cpu_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588104000,
      "name": "cpufreq_cpu_release",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:251",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588104000,
      "name": "cpufreq_cpu_release",
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void cpufreq_cpu_release(struct cpufreq_policy * policy)
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
void cpufreq_cpu_release(struct cpufreq_policy * policy)
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
