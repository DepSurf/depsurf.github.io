# Function: <code>cpu_startup_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579647360,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:281",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647360,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 840
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662944,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:274",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp.c:xen_play_dead",
        "arch/x86/xen/smp.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662944,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 835
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579688224,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:325",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp.c:xen_play_dead",
        "arch/x86/xen/smp.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688224,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674240,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:331",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674240,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579704976,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:331",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579704976,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579649568,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:348",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649568,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687136,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:348",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687136,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720912,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:349",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720912,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763408,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:350",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763408,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579797040,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:367",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797040,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787840,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:392",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787840,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579795984,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:398",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795984,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891920,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:398",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891920,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105024,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:395",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105024,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580278160,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:395",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580278160,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580345456,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:374",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580345456,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580400176,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:404",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580400176,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490942528,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:350",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/arm64/kernel/smp.c:secondary_start_kernel",
        "arch/arm64/kernel/smp.c:secondary_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490942528,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224961176,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:350",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/arm/kernel/smp.c:secondary_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224961176,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283798656,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:350",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/powerpc/kernel/smp.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283798656,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271573384,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:350",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/riscv/kernel/smpboot.c:smp_callin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271573384,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579739264,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:350",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579739264,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669648,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:350",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669648,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579723776,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:350",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579723776,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void cpu_startup_entry(enum cpuhp_state state)
```

```json
{
  "name": "cpu_startup_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771152,
      "name": "cpu_startup_entry",
      "external": true,
      "loc": "kernel/sched/idle.c:350",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771152,
      "name": "cpu_startup_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
