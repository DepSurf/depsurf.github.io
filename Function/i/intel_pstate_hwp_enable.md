# Function: <code>intel_pstate_hwp_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585901296,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:526",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586302256,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:806",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586506971,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1226",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586631802,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1256",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587114891,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1071",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587411008,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1132",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411008,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587591120,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1195",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587591120,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587868256,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1232",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587868256,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588073488,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1278",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588073488,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588931360,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1285",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588931360,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588942352,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1452",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588942352,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588830528,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1452",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588830528,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589525936,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1563",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589525936,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591020560,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1727",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591020560,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1702",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592731376,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071596314869,
      "name": "intel_pstate_hwp_enable.cold",
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1725",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593168512,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071596844286,
      "name": "intel_pstate_hwp_enable.cold",
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1749",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593922048,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    },
    {
      "addr": 18446744071597769411,
      "name": "intel_pstate_hwp_enable.cold",
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587695632,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1278",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587695632,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587471760,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1278",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471760,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588029632,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1278",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588029632,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```

```json
{
  "name": "intel_pstate_hwp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588145104,
      "name": "intel_pstate_hwp_enable",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1278",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588145104,
      "name": "intel_pstate_hwp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void intel_pstate_hwp_enable(struct cpudata * cpudata)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void intel_pstate_hwp_enable(struct cpudata * cpudata)
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
