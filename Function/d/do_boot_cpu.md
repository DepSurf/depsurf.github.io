# Function: <code>do_boot_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579179864,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:944",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
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
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579180272,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:956",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
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
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579190743,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:971",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
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
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579189034,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:974",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
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
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579204829,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:910",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
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
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579216418,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:963",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
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
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579240098,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:964",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1023",
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
      "addr": 18446744071579254320,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 984
    },
    {
      "addr": 18446744071579257688,
      "name": "do_boot_cpu.cold",
      "section": ".text",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1023",
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
      "addr": 18446744071579256032,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
    },
    {
      "addr": 18446744071579259352,
      "name": "do_boot_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579283264,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1036",
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
      "addr": 18446744071579283264,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290544,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1030",
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
      "addr": 18446744071579290544,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
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
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579293264,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1031",
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
      "addr": 18446744071579293264,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1033",
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
      "addr": 18446744071579340192,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
    },
    {
      "addr": 18446744071592072705,
      "name": "do_boot_cpu.cold",
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
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1076",
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
      "addr": 18446744071579401088,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 821
    },
    {
      "addr": 18446744071593839262,
      "name": "do_boot_cpu.cold",
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
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1074",
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
      "addr": 18446744071579481360,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 821
    },
    {
      "addr": 18446744071595965359,
      "name": "do_boot_cpu.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579485184,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1030",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_kick_ap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485184,
      "name": "do_boot_cpu",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int do_boot_cpu(u32 apicid, int cpu, struct task_struct * idle)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515296,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:996",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_kick_ap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515296,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1023",
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
      "addr": 18446744071579254736,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
    },
    {
      "addr": 18446744071579258056,
      "name": "do_boot_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1023",
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
      "addr": 18446744071579189968,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
    },
    {
      "addr": 18446744071579193245,
      "name": "do_boot_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1023",
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
      "addr": 18446744071579255936,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
    },
    {
      "addr": 18446744071579259256,
      "name": "do_boot_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```

```json
{
  "name": "do_boot_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_boot_cpu",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1023",
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
      "addr": 18446744071579261504,
      "name": "do_boot_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 965
    },
    {
      "addr": 18446744071579264856,
      "name": "do_boot_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int * cpu0_nmi_registered</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int apicid</code> ➡️ <code>u32 apicid</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_boot_cpu(int apicid, int cpu, struct task_struct * idle, int * cpu0_nmi_registered)
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
