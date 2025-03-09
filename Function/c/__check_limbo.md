# Function: <code>__check_limbo</code>

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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579124304,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:119",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579124304,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138592,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:119",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138592,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579148560,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:119",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148560,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579214992,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:116",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579214992,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:108",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230259,
      "name": "__check_limbo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579228032,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579230256,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:108",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230256,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579254160,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:108",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254160,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579247040,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:171",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247040,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579248672,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:171",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248672,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579289280,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:171",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579289280,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579343536,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:171",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343536,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413136,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:252",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413136,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425584,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:269",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425584,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579455168,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:269",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579455168,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229104,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:108",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229104,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579164176,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:108",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164176,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579230176,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:108",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230176,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```

```json
{
  "name": "__check_limbo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579235584,
      "name": "__check_limbo",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:108",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235584,
      "name": "__check_limbo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void __check_limbo(struct rdt_domain * d, bool force_free)
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
void __check_limbo(struct rdt_domain * d, bool force_free)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __check_limbo(struct rdt_domain * d, bool force_free)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __check_limbo(struct rdt_domain * d, bool force_free)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __check_limbo(struct rdt_domain * d, bool force_free)
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
