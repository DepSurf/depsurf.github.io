# Function: <code>mce_threshold_remove_device</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579150576,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:1310",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579150576,
      "name": "mce_threshold_remove_device.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
    },
    {
      "addr": 18446744071579153024,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579148624,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:1320",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148624,
      "name": "mce_threshold_remove_device.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
    },
    {
      "addr": 18446744071579151232,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579163552,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:1305",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163552,
      "name": "mce_threshold_remove_device.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 679
    },
    {
      "addr": 18446744071579166064,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579174368,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:1356",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579174368,
      "name": "mce_threshold_remove_device.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    },
    {
      "addr": 18446744071579177360,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579166208,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1356",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579166208,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579178640,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1436",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178640,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579181040,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1442",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181040,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579200400,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1460",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579200400,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579196064,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1460",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196064,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202336,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1460",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202336,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579238704,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1473",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238704,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290208,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1311",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290208,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579355904,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1318",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355904,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579365040,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1314",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365040,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394976,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1364",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394976,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579181296,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1442",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181296,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579114208,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1442",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114208,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579180960,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1442",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180960,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int mce_threshold_remove_device(unsigned int cpu)
```

```json
{
  "name": "mce_threshold_remove_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579186144,
      "name": "mce_threshold_remove_device",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1442",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579186144,
      "name": "mce_threshold_remove_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int mce_threshold_remove_device(unsigned int cpu)
```
</details>
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
int mce_threshold_remove_device(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int mce_threshold_remove_device(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int mce_threshold_remove_device(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int mce_threshold_remove_device(unsigned int cpu)
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
