# Function: <code>pvclock_clocksource_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
cycle_t pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579259280,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:74",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259280,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
cycle_t pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579258656,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:74",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258656,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579272272,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:74",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272272,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268992,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:76",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268992,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579285984,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:78",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579285984,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297392,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:78",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_vcpuop_set_next_event",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297392,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322000,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:78",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_vcpuop_set_next_event",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_sched_clock",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322000,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337200,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:67",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_vcpuop_set_next_event",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_sched_clock",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337200,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579341408,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:67",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_sched_clock",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341408,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579370816,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:67",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_vcpuop_set_next_event",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_sched_clock",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370816,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579369808,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:67",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_vcpuop_set_next_event",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_sched_clock",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369808,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579373536,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:67",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_vcpuop_set_next_event",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_sched_clock",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373536,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:67",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_vcpuop_set_next_event",
        "arch/x86/xen/time.c:xen_timerop_set_next_event",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_sched_clock",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592079960,
      "name": "pvclock_clocksource_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579434864,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:67",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_vcpuop_set_next_event",
        "arch/x86/xen/time.c:xen_timerop_set_next_event",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_sched_clock",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593847198,
      "name": "pvclock_clocksource_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579504320,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:67",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_vcpuop_set_next_event",
        "arch/x86/xen/time.c:xen_timerop_set_next_event",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_sched_clock",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595967769,
      "name": "pvclock_clocksource_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579602224,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_vcpuop_set_next_event",
        "arch/x86/xen/time.c:xen_timerop_set_next_event",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596485386,
      "name": "pvclock_clocksource_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579614976,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_vcpuop_set_next_event",
        "arch/x86/xen/time.c:xen_timerop_set_next_event",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597381996,
      "name": "pvclock_clocksource_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579644032,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337312,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:67",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_sched_clock",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337312,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579269904,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:67",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269904,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337232,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:67",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/xen/time.c:xen_restore_time_memory_area",
        "arch/x86/xen/time.c:xen_save_time_memory_area",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_pvclock_gtod_notify",
        "arch/x86/xen/time.c:xen_sched_clock",
        "arch/x86/xen/time.c:xen_clocksource_get_cycles",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/kernel/kvmclock.c:kvm_sched_clock_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337232,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```

```json
{
  "name": "pvclock_clocksource_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579345680,
      "name": "pvclock_clocksource_read",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:67",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_clocksource_read",
        "arch/x86/kernel/kvmclock.c:kvm_clock_read",
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345680,
      "name": "pvclock_clocksource_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>cycle_t</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
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
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u64 pvclock_clocksource_read(struct pvclock_vcpu_time_info * src)
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
