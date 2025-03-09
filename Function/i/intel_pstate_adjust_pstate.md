# Function: <code>intel_pstate_adjust_pstate</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata * cpu, int target_pstate)
```

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586633680,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1720",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586633680,
      "name": "intel_pstate_adjust_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587113702,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1497",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587413304,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1676",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587593512,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1739",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587868867,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1763",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588074099,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1809",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588938800,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1817",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588938800,
      "name": "intel_pstate_adjust_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
void intel_pstate_adjust_pstate(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588950416,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1965",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588950416,
      "name": "intel_pstate_adjust_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
void intel_pstate_adjust_pstate(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588838416,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1962",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588838416,
      "name": "intel_pstate_adjust_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
void intel_pstate_adjust_pstate(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2120",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589534144,
      "name": "intel_pstate_adjust_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
    },
    {
      "addr": 18446744071592659687,
      "name": "intel_pstate_adjust_pstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void intel_pstate_adjust_pstate(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2289",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591025792,
      "name": "intel_pstate_adjust_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
    },
    {
      "addr": 18446744071594544675,
      "name": "intel_pstate_adjust_pstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void intel_pstate_adjust_pstate(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2251",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592737488,
      "name": "intel_pstate_adjust_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    },
    {
      "addr": 18446744071596315252,
      "name": "intel_pstate_adjust_pstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void intel_pstate_adjust_pstate(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2281",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593174592,
      "name": "intel_pstate_adjust_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    },
    {
      "addr": 18446744071596844669,
      "name": "intel_pstate_adjust_pstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void intel_pstate_adjust_pstate(struct cpudata * cpu)
```

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2305",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593928608,
      "name": "intel_pstate_adjust_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
    },
    {
      "addr": 18446744071597769791,
      "name": "intel_pstate_adjust_pstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587696243,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1809",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587479222,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1809",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588030243,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1809",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_adjust_pstate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588145715,
      "name": "intel_pstate_adjust_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1809",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata * cpu, int target_pstate)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata * cpu, int target_pstate)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata * cpu)
```
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
