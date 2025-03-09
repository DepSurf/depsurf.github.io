# Function: <code>pvclock_set_pvti_cpu0_va</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579286288,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:150",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286288,
      "name": "pvclock_set_pvti_cpu0_va",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297728,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:157",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297728,
      "name": "pvclock_set_pvti_cpu0_va",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322336,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:157",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322336,
      "name": "pvclock_set_pvti_cpu0_va",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:146",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337552,
      "name": "pvclock_set_pvti_cpu0_va.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579337520,
      "name": "pvclock_set_pvti_cpu0_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579341728,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:146",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341728,
      "name": "pvclock_set_pvti_cpu0_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371136,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:146",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_vsyscall_time_info",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371136,
      "name": "pvclock_set_pvti_cpu0_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579370128,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:146",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_vsyscall_time_info",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370128,
      "name": "pvclock_set_pvti_cpu0_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579373872,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:146",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373872,
      "name": "pvclock_set_pvti_cpu0_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435216,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:146",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435216,
      "name": "pvclock_set_pvti_cpu0_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579504704,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:146",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504704,
      "name": "pvclock_set_pvti_cpu0_va",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579602640,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:146",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602640,
      "name": "pvclock_set_pvti_cpu0_va",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579615392,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:156",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615392,
      "name": "pvclock_set_pvti_cpu0_va",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644448,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:156",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644448,
      "name": "pvclock_set_pvti_cpu0_va",
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
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337632,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:146",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337632,
      "name": "pvclock_set_pvti_cpu0_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579270224,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:146",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270224,
      "name": "pvclock_set_pvti_cpu0_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337552,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:146",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337552,
      "name": "pvclock_set_pvti_cpu0_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```

```json
{
  "name": "pvclock_set_pvti_cpu0_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579346000,
      "name": "pvclock_set_pvti_cpu0_va",
      "external": true,
      "loc": "arch/x86/kernel/pvclock.c:146",
      "file": "arch/x86/kernel/pvclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346000,
      "name": "pvclock_set_pvti_cpu0_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```
</details>
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
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void pvclock_set_pvti_cpu0_va(struct pvclock_vsyscall_time_info * pvti)
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
