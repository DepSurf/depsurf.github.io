# Function: <code>irq_lock_sparse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579738832,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:134",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/irq/proc.c:show_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738832,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579761468,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:156",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "kernel/cpu.c:takedown_cpu",
        "kernel/irq/proc.c:show_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760592,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579788492,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:332",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/irq/proc.c:show_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787440,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579786012,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:347",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784960,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579819372,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:345",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818432,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579853237,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:362",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852288,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604722563,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:362",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899280,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604823279,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:377",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934096,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604857628,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:377",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984224,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609188213,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:377",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032528,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612254560,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:379",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016272,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614396106,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:379",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016928,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615330236,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:379",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149152,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617113987,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:379",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293600,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627780645,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504256,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619543525,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:402",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_bringup_ap",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576336,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621842437,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:402",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_bringup_ap",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580640624,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510891232,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:377",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491170688,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243379560,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:377",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225195864,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302525596,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:377",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284070128,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270630998,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:377",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:bringup_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271722824,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604762644,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:377",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952960,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604730516,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:377",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890832,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604840272,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:377",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944496,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void irq_lock_sparse()
```

```json
{
  "name": "irq_lock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604861769,
      "name": "irq_lock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:377",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990848,
      "name": "irq_lock_sparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
