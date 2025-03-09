# Function: <code>flat_cpu_mask_to_apicid_and</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
int flat_cpu_mask_to_apicid_and(const struct cpumask * cpumask, const struct cpumask * andmask, unsigned int * apicid)
```

```json
{
  "name": "flat_cpu_mask_to_apicid_and",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578999280,
      "name": "flat_cpu_mask_to_apicid_and",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:543",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579191648,
      "name": "flat_cpu_mask_to_apicid_and",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:543",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579214784,
      "name": "flat_cpu_mask_to_apicid_and",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:543",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578999280,
      "name": "flat_cpu_mask_to_apicid_and",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579191648,
      "name": "flat_cpu_mask_to_apicid_and",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579214784,
      "name": "flat_cpu_mask_to_apicid_and",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate ❓</summary>

```c
int flat_cpu_mask_to_apicid_and(const struct cpumask * cpumask, const struct cpumask * andmask, unsigned int * apicid)
```

```json
{
  "name": "flat_cpu_mask_to_apicid_and",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578996224,
      "name": "flat_cpu_mask_to_apicid_and",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:550",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579192048,
      "name": "flat_cpu_mask_to_apicid_and",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:550",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579215808,
      "name": "flat_cpu_mask_to_apicid_and",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:550",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578996224,
      "name": "flat_cpu_mask_to_apicid_and",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579192048,
      "name": "flat_cpu_mask_to_apicid_and",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579215808,
      "name": "flat_cpu_mask_to_apicid_and",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
int flat_cpu_mask_to_apicid_and(const struct cpumask * cpumask, const struct cpumask * andmask, unsigned int * apicid)
```

```json
{
  "name": "flat_cpu_mask_to_apicid_and",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578998048,
      "name": "flat_cpu_mask_to_apicid_and",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:550",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579203792,
      "name": "flat_cpu_mask_to_apicid_and",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:550",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579227360,
      "name": "flat_cpu_mask_to_apicid_and",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:550",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998048,
      "name": "flat_cpu_mask_to_apicid_and",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579203792,
      "name": "flat_cpu_mask_to_apicid_and",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579227360,
      "name": "flat_cpu_mask_to_apicid_and",
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int flat_cpu_mask_to_apicid_and(const struct cpumask * cpumask, const struct cpumask * andmask, unsigned int * apicid)
```
</details>
</li>
</ul>
