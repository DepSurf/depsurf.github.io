# Function: <code>kgdb_cpu_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089440,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:467",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_nmicallin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089440,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1419
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122992,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:467",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122992,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1394
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163328,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:467",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163328,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1408
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580169536,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:468",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169536,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1399
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580221936,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:468",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221936,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1407
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:468",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282256,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1384
    },
    {
      "addr": 18446744071580285162,
      "name": "kgdb_cpu_enter.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:525",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580334784,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1407
    },
    {
      "addr": 18446744071580337754,
      "name": "kgdb_cpu_enter.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:525",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387552,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1413
    },
    {
      "addr": 18446744071580390546,
      "name": "kgdb_cpu_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:525",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436272,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1410
    },
    {
      "addr": 18446744071580439330,
      "name": "kgdb_cpu_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:567",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/debug/debug_core.c:kgdb_call_nmi_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518256,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1421
    },
    {
      "addr": 18446744071580521565,
      "name": "kgdb_cpu_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:586",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/debug/debug_core.c:kgdb_call_nmi_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580506320,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1445
    },
    {
      "addr": 18446744071591316336,
      "name": "kgdb_cpu_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:585",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/debug/debug_core.c:kgdb_call_nmi_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580510320,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1502
    },
    {
      "addr": 18446744071591258595,
      "name": "kgdb_cpu_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:582",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/debug/debug_core.c:kgdb_call_nmi_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679024,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2757
    },
    {
      "addr": 18446744071592163792,
      "name": "kgdb_cpu_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:583",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/debug/debug_core.c:kgdb_call_nmi_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889184,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2768
    },
    {
      "addr": 18446744071593936960,
      "name": "kgdb_cpu_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179392,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:571",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/debug/debug_core.c:kgdb_call_nmi_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179392,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2877
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581273616,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:571",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/debug/debug_core.c:kgdb_call_nmi_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273616,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2877
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379680,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:571",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/debug/debug_core.c:kgdb_call_nmi_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379680,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2877
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491704536,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:525",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491704536,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1724
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225657692,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:525",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225657692,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1856
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284726304,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:525",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284726304,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1984
    }
  ]
}
```
</details>
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:525",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580405072,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1410
    },
    {
      "addr": 18446744071580408130,
      "name": "kgdb_cpu_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:525",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580352208,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1376
    },
    {
      "addr": 18446744071580355218,
      "name": "kgdb_cpu_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:525",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580396320,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1410
    },
    {
      "addr": 18446744071580399378,
      "name": "kgdb_cpu_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
```

```json
{
  "name": "kgdb_cpu_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kgdb_cpu_enter",
      "external": false,
      "loc": "kernel/debug/debug_core.c:525",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_nmicallin",
        "kernel/debug/debug_core.c:kgdb_nmicallback",
        "kernel/debug/debug_core.c:kgdb_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451920,
      "name": "kgdb_cpu_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1406
    },
    {
      "addr": 18446744071580454962,
      "name": "kgdb_cpu_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int kgdb_cpu_enter(struct kgdb_state * ks, struct pt_regs * regs, int exception_state)
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
