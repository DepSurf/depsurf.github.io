# Function: <code>vendor_disable_error_reporting</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579121205,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:2073",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579121557,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:2154",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579139631,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:2219",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend"
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
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579137775,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:1951",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend"
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
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579152815,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:1963",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend"
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
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579163375,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:1959",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143040,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1980",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143040,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579155504,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2014",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579155504,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579158000,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2014",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158000,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183888,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2139",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183888,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179376,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2215",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179376,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579185472,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2226",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185472,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2289",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220720,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071592064856,
      "name": "vendor_disable_error_reporting.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271072,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2303",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271072,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334272,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2303",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334272,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579343072,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2319",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343072,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374896,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2348",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374896,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579158368,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2014",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158368,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579094432,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2014",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579094432,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579157920,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2014",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579157920,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void vendor_disable_error_reporting()
```

```json
{
  "name": "vendor_disable_error_reporting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163056,
      "name": "vendor_disable_error_reporting",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2014",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown",
        "arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163056,
      "name": "vendor_disable_error_reporting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void vendor_disable_error_reporting()
```
</details>
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
void vendor_disable_error_reporting()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void vendor_disable_error_reporting()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void vendor_disable_error_reporting()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void vendor_disable_error_reporting()
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
