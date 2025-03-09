# Function: <code>intel_pstate_hwp_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void intel_pstate_hwp_set()
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585898752,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:283",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:store_min_perf_pct",
        "drivers/cpufreq/intel_pstate.c:store_max_perf_pct",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585898752,
      "name": "intel_pstate_hwp_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
void intel_pstate_hwp_set(const struct cpumask * cpumask)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586298784,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:554",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:store_min_perf_pct",
        "drivers/cpufreq/intel_pstate.c:store_max_perf_pct",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586298784,
      "name": "intel_pstate_hwp_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586505120,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:860",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586505120,
      "name": "intel_pstate_hwp_set.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
void intel_pstate_hwp_set(unsigned int cpu)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586630064,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:810",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630064,
      "name": "intel_pstate_hwp_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void intel_pstate_hwp_set(unsigned int cpu)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587112608,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:701",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112608,
      "name": "intel_pstate_hwp_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void intel_pstate_hwp_set(unsigned int cpu)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587411248,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:726",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411248,
      "name": "intel_pstate_hwp_set",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587591360,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:766",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587591360,
      "name": "intel_pstate_hwp_set",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587867888,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:766",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867888,
      "name": "intel_pstate_hwp_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void intel_pstate_hwp_set(unsigned int cpu)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588073120,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:767",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588073120,
      "name": "intel_pstate_hwp_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void intel_pstate_hwp_set(unsigned int cpu)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588932528,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:773",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588932528,
      "name": "intel_pstate_hwp_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
void intel_pstate_hwp_set(unsigned int cpu)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588940608,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:837",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588940608,
      "name": "intel_pstate_hwp_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588836061,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:839",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
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
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589536224,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:926",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
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
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591027488,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:949",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
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
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592740729,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:924",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
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
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593177866,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:944",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
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
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593931710,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:968",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
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
void intel_pstate_hwp_set(unsigned int cpu)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587695264,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:767",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587695264,
      "name": "intel_pstate_hwp_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void intel_pstate_hwp_set(unsigned int cpu)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587471392,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:767",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471392,
      "name": "intel_pstate_hwp_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void intel_pstate_hwp_set(unsigned int cpu)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588029264,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:767",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588029264,
      "name": "intel_pstate_hwp_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void intel_pstate_hwp_set(unsigned int cpu)
```

```json
{
  "name": "intel_pstate_hwp_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588144736,
      "name": "intel_pstate_hwp_set",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:767",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588144736,
      "name": "intel_pstate_hwp_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cpumask * cpumask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void intel_pstate_hwp_set(const struct cpumask * cpumask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu)
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
