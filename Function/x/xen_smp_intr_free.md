# Function: <code>xen_smp_intr_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579020880,
      "name": "xen_smp_intr_free",
      "external": false,
      "loc": "arch/x86/xen/smp.c:118",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_hvm_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579020880,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579017584,
      "name": "xen_smp_intr_free",
      "external": false,
      "loc": "arch/x86/xen/smp.c:118",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_hvm_cpu_up",
        "arch/x86/xen/smp.c:xen_smp_intr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579017584,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579021456,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:118",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_cpu_dead",
        "arch/x86/xen/enlighten.c:xen_cpu_up_prepare",
        "arch/x86/xen/smp.c:xen_smp_intr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021456,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579011872,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:32",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579011872,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579012400,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579012400,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579015040,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015040,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579016544,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579016544,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579024144,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024144,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026416,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026416,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579034544,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034544,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579038224,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038224,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579041056,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041056,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579059984,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579059984,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1114
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579083808,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579083808,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1142
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579118304,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579118304,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1138
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579118816,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cleanup_dead_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579118816,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1138
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579144624,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cleanup_dead_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579144624,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1138
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026768,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026768,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026352,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026352,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void xen_smp_intr_free(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579029920,
      "name": "xen_smp_intr_free",
      "external": true,
      "loc": "arch/x86/xen/smp.c:33",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029920,
      "name": "xen_smp_intr_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void xen_smp_intr_free(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_smp_intr_free(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_smp_intr_free(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_smp_intr_free(unsigned int cpu)
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
void xen_smp_intr_free(unsigned int cpu)
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
