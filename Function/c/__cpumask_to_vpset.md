# Function: <code>__cpumask_to_vpset</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpumask_to_vpset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579072275,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:200",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076175,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:200",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579077711,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:200",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "__cpumask_to_vpset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579097379,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:211",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101404,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:211",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105771,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:211",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int __cpumask_to_vpset(struct hv_vpset * vpset, const struct cpumask * cpus, bool exclude_self)
```

```json
{
  "name": "__cpumask_to_vpset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579133733,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:217",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:217",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ]
    },
    {
      "addr": 0,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:217",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137568,
      "name": "__cpumask_to_vpset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071595958038,
      "name": "__cpumask_to_vpset.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579142352,
      "name": "__cpumask_to_vpset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 18446744071595958089,
      "name": "__cpumask_to_vpset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int __cpumask_to_vpset(struct hv_vpset * vpset, const struct cpumask * cpus, bool (*)(int) func)
```

```json
{
  "name": "__cpumask_to_vpset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579134338,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:220",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138930,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:220",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:220",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143040,
      "name": "__cpumask_to_vpset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    },
    {
      "addr": 18446744071596475455,
      "name": "__cpumask_to_vpset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int __cpumask_to_vpset(struct hv_vpset * vpset, const struct cpumask * cpus, bool (*)(int) func)
```

```json
{
  "name": "__cpumask_to_vpset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579160978,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:228",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165401,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:228",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cpumask_to_vpset",
      "external": false,
      "loc": "include/asm-generic/mshyperv.h:228",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579172416,
      "name": "__cpumask_to_vpset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    },
    {
      "addr": 18446744071597371185,
      "name": "__cpumask_to_vpset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int __cpumask_to_vpset(struct hv_vpset * vpset, const struct cpumask * cpus, bool exclude_self)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool (*)(int) func</code>
</li>
<li>
<b>Param removed. </b>
<code>bool exclude_self</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
