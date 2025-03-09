# Function: <code>wakeup_secondary_cpu_via_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579181051,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:691",
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
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579181335,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:710",
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
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579191844,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:734",
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
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579190126,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:737",
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
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579205984,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:674",
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
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579217466,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:727",
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
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579241146,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:728",
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
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:780",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250736,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071579257209,
      "name": "wakeup_secondary_cpu_via_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:780",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252448,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071579258873,
      "name": "wakeup_secondary_cpu_via_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:793",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277840,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071579285836,
      "name": "wakeup_secondary_cpu_via_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:789",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579285216,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071591258273,
      "name": "wakeup_secondary_cpu_via_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:790",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287744,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071591201403,
      "name": "wakeup_secondary_cpu_via_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:792",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331792,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071592072050,
      "name": "wakeup_secondary_cpu_via_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:835",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579392880,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
    },
    {
      "addr": 18446744071593838590,
      "name": "wakeup_secondary_cpu_via_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579471376,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:833",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471376,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579484544,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:883",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484544,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int wakeup_secondary_cpu_via_init(u32 phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514544,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:849",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514544,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:780",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251152,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071579257577,
      "name": "wakeup_secondary_cpu_via_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:780",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579186400,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071579192766,
      "name": "wakeup_secondary_cpu_via_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:780",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252352,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071579258777,
      "name": "wakeup_secondary_cpu_via_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_init",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:780",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257920,
      "name": "wakeup_secondary_cpu_via_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071579264377,
      "name": "wakeup_secondary_cpu_via_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int phys_apicid</code> ➡️ <code>u32 phys_apicid</code>
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
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip)
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
