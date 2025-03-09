# Function: <code>wrmsr_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583151360,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:65",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu",
        "arch/x86/events/intel/ds.c:fini_debug_store_on_cpu",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151360,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446720,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:65",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:fini_debug_store_on_cpu",
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446720,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583574368,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:65",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:fini_debug_store_on_cpu",
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583574368,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583613264,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:65",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583613264,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583859264,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:66",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859264,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584059728,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584059728,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143856,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143856,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333984,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333984,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584468656,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468656,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585032400,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585032400,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585184288,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585184288,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066240,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066240,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585512976,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585512976,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586663488,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663488,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587911472,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587911472,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588185424,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588185424,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477424,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477424,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584437408,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584437408,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584372432,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584372432,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584420320,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584420320,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```

```json
{
  "name": "wrmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584526368,
      "name": "wrmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:67",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:init_debug_store_on_cpu",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584526368,
      "name": "wrmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int wrmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 l, u32 h)
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
