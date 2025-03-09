# Function: <code>pv_ipi_supported</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pv_ipi_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609135083,
      "name": "pv_ipi_supported",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:444",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask",
        "arch/x86/kernel/kvm.c:kvm_apic_init"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pv_ipi_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612203741,
      "name": "pv_ipi_supported",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:465",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask",
        "arch/x86/kernel/kvm.c:kvm_apic_init"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pv_ipi_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614344537,
      "name": "pv_ipi_supported",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:463",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool pv_ipi_supported()
```

```json
{
  "name": "pv_ipi_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592079682,
      "name": "pv_ipi_supported",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:464",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592079682,
      "name": "pv_ipi_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
bool pv_ipi_supported()
```

```json
{
  "name": "pv_ipi_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593846937,
      "name": "pv_ipi_supported",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:484",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593846937,
      "name": "pv_ipi_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pv_ipi_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627696421,
      "name": "pv_ipi_supported",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:483",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pv_ipi_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619454165,
      "name": "pv_ipi_supported",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:483",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pv_ipi_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621750341,
      "name": "pv_ipi_supported",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:484",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool pv_ipi_supported()
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool pv_ipi_supported()
```
</details>
</li>
</ul>
