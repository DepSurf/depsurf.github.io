# Function: <code>xen_smp_intr_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579021424,
      "name": "xen_smp_intr_init",
      "external": false,
      "loc": "arch/x86/xen/smp.c:162",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_hvm_cpu_up",
        "arch/x86/xen/smp.c:xen_hvm_cpu_up",
        "arch/x86/xen/smp.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021424,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579018128,
      "name": "xen_smp_intr_init",
      "external": false,
      "loc": "arch/x86/xen/smp.c:162",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_hvm_cpu_up",
        "arch/x86/xen/smp.c:xen_hvm_cpu_up",
        "arch/x86/xen/smp.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018128,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579022192,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:162",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_cpu_up_prepare",
        "arch/x86/xen/smp.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579022192,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579012240,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:61",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579012240,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579012768,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579012768,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579015408,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015408,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579016912,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579016912,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579024512,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024512,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026784,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026784,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579034912,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034912,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579038592,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038592,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579041424,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041424,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592049496,
      "name": "xen_smp_intr_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579061104,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593815839,
      "name": "xen_smp_intr_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579084960,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595957827,
      "name": "xen_smp_intr_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579119472,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596475064,
      "name": "xen_smp_intr_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579119984,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597370405,
      "name": "xen_smp_intr_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579145792,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 840
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579027136,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579027136,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026720,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026720,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int xen_smp_intr_init(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579030288,
      "name": "xen_smp_intr_init",
      "external": true,
      "loc": "arch/x86/xen/smp.c:62",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579030288,
      "name": "xen_smp_intr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int xen_smp_intr_init(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int xen_smp_intr_init(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xen_smp_intr_init(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xen_smp_intr_init(unsigned int cpu)
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
int xen_smp_intr_init(unsigned int cpu)
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
