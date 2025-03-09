# Function: <code>irq_unlock_sparse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579738864,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:139",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/irq/proc.c:show_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738864,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579761487,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:161",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/irq/proc.c:show_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760624,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579788511,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:337",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/irq/proc.c:show_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787472,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579786031,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:352",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784992,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579819391,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:350",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818464,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579853272,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:367",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852320,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604722613,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:367",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899312,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604823327,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934128,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604857676,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984256,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609188261,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032560,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612254608,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:384",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016304,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614396154,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:384",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016960,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615330284,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:384",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149184,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617114035,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:384",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293632,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627780811,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:387",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504304,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619543691,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:407",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_bringup_ap",
        "kernel/cpu.c:cpuhp_bringup_ap",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576384,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621842603,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:407",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_bringup_ap",
        "kernel/cpu.c:cpuhp_bringup_ap",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580640672,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510891272,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491170728,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243379620,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225195900,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302525668,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284070192,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270631048,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:bringup_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271722866,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604762692,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952992,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604730564,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890864,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604840320,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944528,
      "name": "irq_unlock_sparse",
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
void irq_unlock_sparse()
```

```json
{
  "name": "irq_unlock_sparse",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604861817,
      "name": "irq_unlock_sparse",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:382",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990880,
      "name": "irq_unlock_sparse",
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
