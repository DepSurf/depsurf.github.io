# Function: <code>native_apic_msr_eoi</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_apic_msr_eoi()
```

```json
{
  "name": "native_apic_msr_eoi",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579573952,
      "name": "native_apic_msr_eoi",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:198",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579576992,
      "name": "native_apic_msr_eoi",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:198",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579578784,
      "name": "native_apic_msr_eoi",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:198",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573952,
      "name": "native_apic_msr_eoi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579576992,
      "name": "native_apic_msr_eoi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579578784,
      "name": "native_apic_msr_eoi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void native_apic_msr_eoi()
```
</details>
</li>
</ul>
