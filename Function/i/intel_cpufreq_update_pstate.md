# Function: <code>intel_cpufreq_update_pstate</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int intel_cpufreq_update_pstate(struct cpufreq_policy * policy, int target_pstate, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_update_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588952592,
      "name": "intel_cpufreq_update_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2565",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588952592,
      "name": "intel_cpufreq_update_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int intel_cpufreq_update_pstate(struct cpufreq_policy * policy, int target_pstate, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_update_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588841040,
      "name": "intel_cpufreq_update_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2544",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588841040,
      "name": "intel_cpufreq_update_pstate",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_cpufreq_update_pstate(struct cpufreq_policy * policy, int target_pstate, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_update_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_cpufreq_update_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2715",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589537504,
      "name": "intel_cpufreq_update_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071592660058,
      "name": "intel_cpufreq_update_pstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int intel_cpufreq_update_pstate(struct cpufreq_policy * policy, int target_pstate, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_update_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_cpufreq_update_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2881",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591029824,
      "name": "intel_cpufreq_update_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071594545157,
      "name": "intel_cpufreq_update_pstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int intel_cpufreq_update_pstate(struct cpufreq_policy * policy, int target_pstate, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_update_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_cpufreq_update_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2845",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592739344,
      "name": "intel_cpufreq_update_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071596315291,
      "name": "intel_cpufreq_update_pstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int intel_cpufreq_update_pstate(struct cpufreq_policy * policy, int target_pstate, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_update_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_cpufreq_update_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2871",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593176448,
      "name": "intel_cpufreq_update_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071596844708,
      "name": "intel_cpufreq_update_pstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int intel_cpufreq_update_pstate(struct cpufreq_policy * policy, int target_pstate, bool fast_switch)
```

```json
{
  "name": "intel_cpufreq_update_pstate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_cpufreq_update_pstate",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2895",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593930400,
      "name": "intel_cpufreq_update_pstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071597769830,
      "name": "intel_cpufreq_update_pstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int intel_cpufreq_update_pstate(struct cpufreq_policy * policy, int target_pstate, bool fast_switch)
```
</details>
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
