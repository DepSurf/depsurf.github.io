# Function: <code>mce_available</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579132000,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:442",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_restart",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132000,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579131984,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:485",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579131984,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579139296,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:510",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139296,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579137456,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:441",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137456,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579152496,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:450",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152496,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579163056,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:447",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163056,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579152560,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:445",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152560,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579164576,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:462",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164576,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579167024,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:462",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579167024,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579184542,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:444",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579186576,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579180782,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:510",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579182768,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579186782,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:510",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579189088,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579221295,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:519",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224096,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579271678,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:444",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275072,
      "name": "mce_available",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627601553,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:444",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339440,
      "name": "mce_available",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619355617,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:438",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348320,
      "name": "mce_available",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621649633,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:469",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378176,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579167376,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:462",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579167376,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579098976,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:462",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098976,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579166944,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:462",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579166944,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mce_available(struct cpuinfo_x86 * c)
```

```json
{
  "name": "mce_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579172128,
      "name": "mce_available",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:462",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_cmci",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_clear",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579172128,
      "name": "mce_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
int mce_available(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int mce_available(struct cpuinfo_x86 * c)
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
