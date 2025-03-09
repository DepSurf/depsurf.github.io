# Function: <code>arch_match_cpu_phys_id</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```

```json
{
  "name": "arch_match_cpu_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579300720,
      "name": "arch_match_cpu_phys_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2337",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300720,
      "name": "arch_match_cpu_phys_id",
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
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```

```json
{
  "name": "arch_match_cpu_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579303584,
      "name": "arch_match_cpu_phys_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2345",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303584,
      "name": "arch_match_cpu_phys_id",
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
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```

```json
{
  "name": "arch_match_cpu_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579351248,
      "name": "arch_match_cpu_phys_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2342",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351248,
      "name": "arch_match_cpu_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```

```json
{
  "name": "arch_match_cpu_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413136,
      "name": "arch_match_cpu_phys_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2350",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413136,
      "name": "arch_match_cpu_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```

```json
{
  "name": "arch_match_cpu_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579495280,
      "name": "arch_match_cpu_phys_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2384",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495280,
      "name": "arch_match_cpu_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```

```json
{
  "name": "arch_match_cpu_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507536,
      "name": "arch_match_cpu_phys_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2387",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507536,
      "name": "arch_match_cpu_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```

```json
{
  "name": "arch_match_cpu_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536288,
      "name": "arch_match_cpu_phys_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:2323",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536288,
      "name": "arch_match_cpu_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```

```json
{
  "name": "arch_match_cpu_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490219040,
      "name": "arch_match_cpu_phys_id",
      "external": true,
      "loc": "arch/arm64/kernel/setup.c:100",
      "file": "arch/arm64/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/base.c:arch_find_n_match_cpu_physical_id",
        "drivers/of/base.c:arch_find_n_match_cpu_physical_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490219040,
      "name": "arch_match_cpu_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```

```json
{
  "name": "arch_match_cpu_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224459916,
      "name": "arch_match_cpu_phys_id",
      "external": true,
      "loc": "arch/arm/kernel/devtree.c:186",
      "file": "arch/arm/kernel/devtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/base.c:arch_find_n_match_cpu_physical_id",
        "drivers/of/base.c:arch_find_n_match_cpu_physical_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224459916,
      "name": "arch_match_cpu_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```

```json
{
  "name": "arch_match_cpu_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282345152,
      "name": "arch_match_cpu_phys_id",
      "external": true,
      "loc": "arch/powerpc/kernel/prom.c:889",
      "file": "arch/powerpc/kernel/prom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/base.c:__of_find_n_match_cpu_property",
        "drivers/of/base.c:__of_find_n_match_cpu_property"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282345152,
      "name": "arch_match_cpu_phys_id",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```

```json
{
  "name": "arch_match_cpu_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271351140,
      "name": "arch_match_cpu_phys_id",
      "external": true,
      "loc": "arch/riscv/kernel/smp.c:66",
      "file": "arch/riscv/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/base.c:arch_find_n_match_cpu_physical_id",
        "drivers/of/base.c:arch_find_n_match_cpu_physical_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271351140,
      "name": "arch_match_cpu_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
bool arch_match_cpu_phys_id(int cpu, u64 phys_id)
```
</details>
</li>
</ul>
