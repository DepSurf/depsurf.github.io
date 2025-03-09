# Function: <code>rdt_cpu_has</code>

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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596336882,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:699",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596336882,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 73
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602655050,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:702",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602655050,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 76
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602826230,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:772",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602826230,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 68
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604632687,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:810",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604632687,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 69
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604729798,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:802",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604729798,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 75
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604742911,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:802",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604742911,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 75
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609088962,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:804",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609088962,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 75
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612152725,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:808",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612152725,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 75
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614292441,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:808",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614292441,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 67
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615218747,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:749",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615218747,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 133
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616992554,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:749",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616992554,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 141
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627617712,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:702",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627617712,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619373280,
      "name": "rdt_cpu_has",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:731",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config",
        "arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config",
        "arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619373280,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 184
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621668560,
      "name": "rdt_cpu_has",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:735",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config",
        "arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config",
        "arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621668560,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 184
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604669214,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:802",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604669214,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 75
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604636818,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:802",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604636818,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 75
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604746977,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:802",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604746977,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 75
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
bool rdt_cpu_has(int flag)
```

```json
{
  "name": "rdt_cpu_has",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604747023,
      "name": "rdt_cpu_has",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:802",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604747023,
      "name": "rdt_cpu_has",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 75
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
bool rdt_cpu_has(int flag)
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
bool rdt_cpu_has(int flag)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool rdt_cpu_has(int flag)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool rdt_cpu_has(int flag)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool rdt_cpu_has(int flag)
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
