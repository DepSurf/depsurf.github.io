# Function: <code>common_cpu_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179520,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:920",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179520,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179920,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:932",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179920,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579190723,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:948",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190400,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579189014,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:951",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188688,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579204809,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:888",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204480,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579216365,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:941",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216080,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579240045,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:942",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579239760,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579255312,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:994",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255312,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579256976,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:994",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256976,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579284298,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1007",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283952,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291232,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1000",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291232,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579293936,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1001",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293936,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579340928,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1003",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579340928,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579401920,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1046",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401920,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579482208,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1044",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482208,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579487033,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1002",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_kick_ap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494608,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579517039,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:968",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_kick_ap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524560,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579255680,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:994",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255680,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579190912,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:994",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190912,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579256880,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:994",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256880,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```

```json
{
  "name": "common_cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579262480,
      "name": "common_cpu_up",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:994",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262480,
      "name": "common_cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct * idle)
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
