# Function: <code>flat_vector_allocation_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void flat_vector_allocation_domain(int cpu, struct cpumask * retmask, const struct cpumask * mask)
```

```json
{
  "name": "flat_vector_allocation_domain",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578999568,
      "name": "flat_vector_allocation_domain",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:566",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579214896,
      "name": "flat_vector_allocation_domain",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:566",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578999568,
      "name": "flat_vector_allocation_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579214896,
      "name": "flat_vector_allocation_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void flat_vector_allocation_domain(int cpu, struct cpumask * retmask, const struct cpumask * mask)
```

```json
{
  "name": "flat_vector_allocation_domain",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578996496,
      "name": "flat_vector_allocation_domain",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:573",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579215840,
      "name": "flat_vector_allocation_domain",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:573",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578996496,
      "name": "flat_vector_allocation_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579215840,
      "name": "flat_vector_allocation_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void flat_vector_allocation_domain(int cpu, struct cpumask * retmask, const struct cpumask * mask)
```

```json
{
  "name": "flat_vector_allocation_domain",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578998256,
      "name": "flat_vector_allocation_domain",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:573",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579227392,
      "name": "flat_vector_allocation_domain",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:573",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998256,
      "name": "flat_vector_allocation_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071579227392,
      "name": "flat_vector_allocation_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
void flat_vector_allocation_domain(int cpu, struct cpumask * retmask, const struct cpumask * mask)
```

```json
{
  "name": "flat_vector_allocation_domain",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578959776,
      "name": "flat_vector_allocation_domain",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:553",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579225088,
      "name": "flat_vector_allocation_domain",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:553",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578959776,
      "name": "flat_vector_allocation_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071579225088,
      "name": "flat_vector_allocation_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void flat_vector_allocation_domain(int cpu, struct cpumask * retmask, const struct cpumask * mask)
```
</details>
</li>
</ul>
