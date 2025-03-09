# Function: <code>_cpu_down</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374848,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:339",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_down",
        "kernel/cpu.c:disable_nonboot_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374848,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587834128,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:796",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587834128,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588049504,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:762",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588049504,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588276656,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:685",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588276656,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588842208,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:854",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588842208,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589221424,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:940",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589221424,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589463648,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:955",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589463648,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589923712,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:967",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589923712,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590149824,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:976",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590149824,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591168448,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:992",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591168448,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591664208,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:996",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591664208,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591608032,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:1096",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591608032,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592781408,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:1120",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592781408,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594679520,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:1126",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594679520,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596415312,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:1152",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596415312,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596955168,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:1404",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:__cpu_down_maps_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596955168,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597882688,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:1439",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:__cpu_down_maps_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597882688,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503901416,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:976",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503901416,
      "name": "_cpu_down",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236529024,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:976",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236529024,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283479632,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:976",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283479632,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589752112,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:976",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589752112,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589476336,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:976",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589476336,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590195520,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:976",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590195520,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
```

```json
{
  "name": "_cpu_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590245952,
      "name": "_cpu_down",
      "external": false,
      "loc": "kernel/cpu.c:976",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:do_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590245952,
      "name": "_cpu_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cpuhp_state target</code>
</li>
</ul>
</details>
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
int _cpu_down(unsigned int cpu, int tasks_frozen, enum cpuhp_state target)
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
