# Function: <code>x86_read_arch_cap_msr</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579132352,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1098",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132352,
      "name": "x86_read_arch_cap_msr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579136192,
      "name": "x86_read_arch_cap_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579152128,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1104",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:srbds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152128,
      "name": "x86_read_arch_cap_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579149296,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1122",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:srbds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579149296,
      "name": "x86_read_arch_cap_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579155504,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1123",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579155504,
      "name": "x86_read_arch_cap_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579184880,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1126",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184880,
      "name": "x86_read_arch_cap_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579232432,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1281",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579232432,
      "name": "x86_read_arch_cap_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627586640,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1304",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291296,
      "name": "x86_read_arch_cap_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619339024,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1303",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297872,
      "name": "x86_read_arch_cap_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621631744,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1328",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:bhi_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:rfds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327296,
      "name": "x86_read_arch_cap_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579132736,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1098",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132736,
      "name": "x86_read_arch_cap_msr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579136576,
      "name": "x86_read_arch_cap_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604621084,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1098",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579067136,
      "name": "x86_read_arch_cap_msr",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579132288,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1098",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132288,
      "name": "x86_read_arch_cap_msr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579136128,
      "name": "x86_read_arch_cap_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u64 x86_read_arch_cap_msr()
```

```json
{
  "name": "x86_read_arch_cap_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579137408,
      "name": "x86_read_arch_cap_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1098",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137408,
      "name": "x86_read_arch_cap_msr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579141248,
      "name": "x86_read_arch_cap_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
u64 x86_read_arch_cap_msr()
```
</details>
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
u64 x86_read_arch_cap_msr()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u64 x86_read_arch_cap_msr()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u64 x86_read_arch_cap_msr()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u64 x86_read_arch_cap_msr()
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
