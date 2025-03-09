# Function: <code>hv_set_register</code>

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
  "name": "hv_set_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614650865,
      "name": "hv_set_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:18",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
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
  "name": "hv_set_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615609803,
      "name": "hv_set_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:18",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
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
  "name": "hv_set_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617419777,
      "name": "hv_set_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:212",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
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
  "name": "hv_set_register",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579129609,
      "name": "hv_set_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:210",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628173563,
      "name": "hv_set_register",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:210",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
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
void hv_set_register(unsigned int reg, u64 value)
```

```json
{
  "name": "hv_set_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_set_register",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mshyperv.c:99",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event",
        "drivers/hv/hv_common.c:hv_kmsg_dump",
        "drivers/hv/hv_common.c:hv_kmsg_dump",
        "drivers/hv/hv_common.c:hv_kmsg_dump",
        "drivers/hv/hv_common.c:hv_kmsg_dump",
        "drivers/hv/hv_common.c:hv_kmsg_dump",
        "drivers/hv/hv_common.c:hv_kmsg_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596482525,
      "name": "hv_set_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579472016,
      "name": "hv_set_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void hv_set_register(unsigned int reg, u64 value)
```

```json
{
  "name": "hv_set_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_set_register",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mshyperv.c:104",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event",
        "drivers/hv/hv_common.c:hv_kmsg_dump",
        "drivers/hv/hv_common.c:hv_kmsg_dump",
        "drivers/hv/hv_common.c:hv_kmsg_dump",
        "drivers/hv/hv_common.c:hv_kmsg_dump",
        "drivers/hv/hv_common.c:hv_kmsg_dump",
        "drivers/hv/hv_common.c:hv_kmsg_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597378625,
      "name": "hv_set_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579502320,
      "name": "hv_set_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void hv_set_register(unsigned int reg, u64 value)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
