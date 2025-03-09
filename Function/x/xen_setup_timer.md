# Function: <code>xen_setup_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578991072,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:408",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_hvm_cpu_notify",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991072,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578987648,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:317",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_hvm_cpu_notify",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987648,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578989520,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:317",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_cpu_up_prepare",
        "arch/x86/xen/time.c:xen_time_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989520,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578955920,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:320",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578955920,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578958224,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:321",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958224,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578960752,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:321",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578960752,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578959504,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:328",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578959504,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:328",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967007,
      "name": "xen_setup_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071578966480,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:328",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969433,
      "name": "xen_setup_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071578968944,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:335",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578979032,
      "name": "xen_setup_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071578978288,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:336",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591241669,
      "name": "xen_setup_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071578980912,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:336",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591184743,
      "name": "xen_setup_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071578990032,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:336",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592046537,
      "name": "xen_setup_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071579006992,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:336",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593812936,
      "name": "xen_setup_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071579024304,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579052352,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:336",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052352,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579052256,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:344",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052256,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077584,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:344",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077584,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:328",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969449,
      "name": "xen_setup_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071578968960,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:328",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969369,
      "name": "xen_setup_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071578968880,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void xen_setup_timer(int cpu)
```

```json
{
  "name": "xen_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_setup_timer",
      "external": true,
      "loc": "arch/x86/xen/time.c:328",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969965,
      "name": "xen_setup_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071578969504,
      "name": "xen_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void xen_setup_timer(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_setup_timer(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_setup_timer(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_setup_timer(int cpu)
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
void xen_setup_timer(int cpu)
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
