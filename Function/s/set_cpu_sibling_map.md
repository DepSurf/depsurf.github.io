# Function: <code>set_cpu_sibling_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579177152,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:485",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579177152,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1246
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579177536,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:500",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579177536,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1293
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188080,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:524",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus",
        "arch/x86/xen/smp.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188080,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1321
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579186384,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:527",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579186384,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1297
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202112,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:464",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202112,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1228
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579214064,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:517",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579214064,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1270
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579237744,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:517",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237744,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1270
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579252224,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:565",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252224,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1423
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579253936,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:565",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253936,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1423
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579281088,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:578",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:smp_callin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281088,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1503
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579288464,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:573",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:smp_callin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288464,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1503
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291232,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:575",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291232,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1447
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579336400,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:574",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579336400,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3158
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396944,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:608",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396944,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3547
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579476368,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:606",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476368,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3841
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489920,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:668",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489920,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3841
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520208,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:671",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520208,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3953
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579252640,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:565",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252640,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1423
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579187888,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:565",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187888,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1423
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579253840,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:565",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253840,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1423
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
void set_cpu_sibling_map(int cpu)
```

```json
{
  "name": "set_cpu_sibling_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579259408,
      "name": "set_cpu_sibling_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:565",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259408,
      "name": "set_cpu_sibling_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1423
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
void set_cpu_sibling_map(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void set_cpu_sibling_map(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void set_cpu_sibling_map(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void set_cpu_sibling_map(int cpu)
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
