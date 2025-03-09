# Function: <code>mbm_setup_overflow_handler</code>

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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579125568,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:396",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579125568,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139856,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:396",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139856,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579150208,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:552",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579150208,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579216640,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:549",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216640,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229696,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:541",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229696,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579231936,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:541",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231936,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579255248,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:545",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255248,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579248080,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:597",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248080,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579249984,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:596",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249984,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290576,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:611",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290576,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579345040,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:611",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345040,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414928,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:692",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414928,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579427376,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:704",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427376,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456960,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:704",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456960,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579230784,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:541",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230784,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579166064,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:541",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579166064,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579231856,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:541",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231856,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```

```json
{
  "name": "mbm_setup_overflow_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579237296,
      "name": "mbm_setup_overflow_handler",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:541",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237296,
      "name": "mbm_setup_overflow_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
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
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void mbm_setup_overflow_handler(struct rdt_domain * dom, long unsigned int delay_ms)
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
