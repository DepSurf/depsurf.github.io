# Function: <code>pvclock_read_wallclock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579259488,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:118",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259488,
      "name": "pvclock_read_wallclock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579258832,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:120",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258832,
      "name": "pvclock_read_wallclock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579272448,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:120",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272448,
      "name": "pvclock_read_wallclock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579269168,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:122",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269168,
      "name": "pvclock_read_wallclock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579286160,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:124",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286160,
      "name": "pvclock_read_wallclock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297584,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:124",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297584,
      "name": "pvclock_read_wallclock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322192,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:124",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322192,
      "name": "pvclock_read_wallclock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337392,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337392,
      "name": "pvclock_read_wallclock",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579341600,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341600,
      "name": "pvclock_read_wallclock",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371008,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371008,
      "name": "pvclock_read_wallclock",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579370000,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370000,
      "name": "pvclock_read_wallclock",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579373744,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373744,
      "name": "pvclock_read_wallclock",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435088,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435088,
      "name": "pvclock_read_wallclock",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579504560,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504560,
      "name": "pvclock_read_wallclock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579602480,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602480,
      "name": "pvclock_read_wallclock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579615232,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:123",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615232,
      "name": "pvclock_read_wallclock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644288,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:123",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644288,
      "name": "pvclock_read_wallclock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337504,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337504,
      "name": "pvclock_read_wallclock",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579270096,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270096,
      "name": "pvclock_read_wallclock",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337424,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337424,
      "name": "pvclock_read_wallclock",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```

```json
{
  "name": "pvclock_read_wallclock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579345872,
      "name": "pvclock_read_wallclock",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:113",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_read_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345872,
      "name": "pvclock_read_wallclock",
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec * ts</code> ➡️ <code>struct timespec64 * ts</code>
</li>
</ul>
</details>
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
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void pvclock_read_wallclock(struct pvclock_wall_clock * wall_clock, struct pvclock_vcpu_time_info * vcpu_time, struct timespec64 * ts)
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
