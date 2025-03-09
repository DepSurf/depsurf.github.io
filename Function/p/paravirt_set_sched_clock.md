# Function: <code>paravirt_set_sched_clock</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void paravirt_set_sched_clock(u64 (*)() func)
```

```json
{
  "name": "paravirt_set_sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579372800,
      "name": "paravirt_set_sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:135",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_init_time_common",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372800,
      "name": "paravirt_set_sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void paravirt_set_sched_clock(u64 (*)() func)
```

```json
{
  "name": "paravirt_set_sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579434096,
      "name": "paravirt_set_sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:135",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_init_time_common",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434096,
      "name": "paravirt_set_sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void paravirt_set_sched_clock(u64 (*)() func)
```

```json
{
  "name": "paravirt_set_sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503264,
      "name": "paravirt_set_sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:131",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_init_time_common",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503264,
      "name": "paravirt_set_sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void paravirt_set_sched_clock(u64 (*)() func)
```

```json
{
  "name": "paravirt_set_sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600832,
      "name": "paravirt_set_sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:114",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600832,
      "name": "paravirt_set_sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void paravirt_set_sched_clock(u64 (*)() func)
```

```json
{
  "name": "paravirt_set_sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613584,
      "name": "paravirt_set_sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:115",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613584,
      "name": "paravirt_set_sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void paravirt_set_sched_clock(u64 (*)() func)
```

```json
{
  "name": "paravirt_set_sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643296,
      "name": "paravirt_set_sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:79",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643296,
      "name": "paravirt_set_sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void paravirt_set_sched_clock(u64 (*)() func)
```
</details>
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
