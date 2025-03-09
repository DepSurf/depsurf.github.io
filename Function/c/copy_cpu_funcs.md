# Function: <code>copy_cpu_funcs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595313329,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1231",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595495922,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1623",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595495922,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 93
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595749009,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2341",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595749009,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 113
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596677642,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2403",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596677642,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 146
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603007746,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2134",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603007746,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603180281,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2367",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603180281,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604990501,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2442",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604990501,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605102368,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2471",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605102368,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605141783,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2577",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605141783,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609412811,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2591",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609412811,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612486358,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2891",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612486358,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614628682,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2871",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614628682,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615585038,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:3063",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615585038,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617393421,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:3231",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617393421,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071628142210,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:3195",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
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
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619909106,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:3221",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
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
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622219138,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:3237",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605033041,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2577",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605033041,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605000724,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2577",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605000724,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605118819,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2577",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605118819,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```

```json
{
  "name": "copy_cpu_funcs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605145977,
      "name": "copy_cpu_funcs",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2577",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605145977,
      "name": "copy_cpu_funcs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 98
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void copy_cpu_funcs(struct pstate_funcs * funcs)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void copy_cpu_funcs(struct pstate_funcs * funcs)
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
void copy_cpu_funcs(struct pstate_funcs * funcs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void copy_cpu_funcs(struct pstate_funcs * funcs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void copy_cpu_funcs(struct pstate_funcs * funcs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void copy_cpu_funcs(struct pstate_funcs * funcs)
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
