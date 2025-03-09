# Function: <code>hv_get_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hv_get_register",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579047469,
      "name": "hv_get_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:23",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614650834,
      "name": "hv_get_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:23",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc"
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
  "name": "hv_get_register",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615609772,
      "name": "hv_get_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:23",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589728405,
      "name": "hv_get_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:23",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv_common.c:__hv_read_ref_counter",
        "drivers/hv/hv_common.c:hv_common_cpu_init"
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
  "name": "hv_get_register",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617419747,
      "name": "hv_get_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:201",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591237429,
      "name": "hv_get_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:201",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv_common.c:__hv_read_ref_counter",
        "drivers/hv/hv_common.c:hv_common_cpu_init"
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
  "name": "hv_get_register",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579129593,
      "name": "hv_get_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:199",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628173457,
      "name": "hv_get_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:199",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592989253,
      "name": "hv_get_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:199",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv_common.c:__hv_read_ref_counter",
        "drivers/hv/hv_common.c:hv_common_cpu_init"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
u64 hv_get_register(unsigned int reg)
```

```json
{
  "name": "hv_get_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_get_register",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mshyperv.c:90",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/hv/hv_common.c:__hv_read_ref_counter",
        "drivers/hv/hv_common.c:hv_common_cpu_init",
        "drivers/hv/hv_common.c:hv_common_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596482504,
      "name": "hv_get_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579471696,
      "name": "hv_get_register",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
u64 hv_get_register(unsigned int reg)
```

```json
{
  "name": "hv_get_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_get_register",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mshyperv.c:95",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/hv/hv_common.c:__hv_read_ref_counter",
        "drivers/hv/hv_common.c:hv_common_cpu_init",
        "drivers/hv/hv_common.c:hv_common_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597378604,
      "name": "hv_get_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579501920,
      "name": "hv_get_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
u64 hv_get_register(unsigned int reg)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
