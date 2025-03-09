# Function: <code>xen_vcpu_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578960144,
      "name": "xen_vcpu_setup",
      "external": false,
      "loc": "arch/x86/xen/enlighten.c:182",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_hvm_cpu_notify",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten.c:xen_setup_vcpu_info_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578960144,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
void xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578961424,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:185",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_hvm_cpu_notify",
        "arch/x86/xen/enlighten.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578961424,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578963168,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:187",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_cpu_up_prepare",
        "arch/x86/xen/enlighten.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963168,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578949936,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:185",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578949936,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578952208,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:189",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578952208,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:197",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578955893,
      "name": "xen_vcpu_setup.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071578954736,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:199",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957913,
      "name": "xen_vcpu_setup.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071578956736,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:199",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964878,
      "name": "xen_vcpu_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071578963680,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:199",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967342,
      "name": "xen_vcpu_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071578966112,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:199",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578976542,
      "name": "xen_vcpu_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071578975440,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:199",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591241355,
      "name": "xen_vcpu_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071578978160,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:199",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591184640,
      "name": "xen_vcpu_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071578987280,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:203",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592046270,
      "name": "xen_vcpu_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579003488,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
void xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:157",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593812759,
      "name": "xen_vcpu_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579020352,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
void xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048064,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:157",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048064,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048064,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:157",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048064,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073392,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:160",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073392,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:199",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967342,
      "name": "xen_vcpu_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071578966112,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:199",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967278,
      "name": "xen_vcpu_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071578966048,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int xen_vcpu_setup(int cpu)
```

```json
{
  "name": "xen_vcpu_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_vcpu_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:199",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967870,
      "name": "xen_vcpu_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071578966640,
      "name": "xen_vcpu_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
int xen_vcpu_setup(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int xen_vcpu_setup(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xen_vcpu_setup(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xen_vcpu_setup(int cpu)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int xen_vcpu_setup(int cpu)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
