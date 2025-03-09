# Function: <code>kvm_disable_steal_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579253904,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:419",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253904,
      "name": "kvm_disable_steal_time.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579254576,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579253750,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:410",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252896,
      "name": "kvm_disable_steal_time.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579253584,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579267248,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:407",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266384,
      "name": "kvm_disable_steal_time.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579267072,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579263872,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:414",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263024,
      "name": "kvm_disable_steal_time.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579263696,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579280768,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:421",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279232,
      "name": "kvm_disable_steal_time.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579280592,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579292128,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:421",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290512,
      "name": "kvm_disable_steal_time.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579291952,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579317168,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:412",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315360,
      "name": "kvm_disable_steal_time.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579316992,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579332416,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:396",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329904,
      "name": "kvm_disable_steal_time.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579332240,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579336592,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:396",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334016,
      "name": "kvm_disable_steal_time.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579336416,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579366000,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:398",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365808,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579365152,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:419",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579364960,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579369365,
      "name": "kvm_disable_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:379",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579430357,
      "name": "kvm_disable_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:379",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579498901,
      "name": "kvm_disable_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:396",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579595445,
      "name": "kvm_disable_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:395",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579608229,
      "name": "kvm_disable_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:395",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579637989,
      "name": "kvm_disable_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:395",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579332496,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:396",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329920,
      "name": "kvm_disable_steal_time.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579332320,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579266971,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:396",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266032,
      "name": "kvm_disable_steal_time.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579267696,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579332416,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:396",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329840,
      "name": "kvm_disable_steal_time.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579332240,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kvm_disable_steal_time()
```

```json
{
  "name": "kvm_disable_steal_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579340720,
      "name": "kvm_disable_steal_time",
      "external": true,
      "loc": "arch/x86/kernel/kvm.c:396",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338496,
      "name": "kvm_disable_steal_time.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579340544,
      "name": "kvm_disable_steal_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void kvm_disable_steal_time()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void kvm_disable_steal_time()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void kvm_disable_steal_time()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void kvm_disable_steal_time()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void kvm_disable_steal_time()
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
