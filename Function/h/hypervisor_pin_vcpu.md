# Function: <code>hypervisor_pin_vcpu</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void hypervisor_pin_vcpu(int cpu)
```

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179712,
      "name": "hypervisor_pin_vcpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:90",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179712,
      "name": "hypervisor_pin_vcpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void hypervisor_pin_vcpu(int cpu)
```

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579178416,
      "name": "hypervisor_pin_vcpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:85",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178416,
      "name": "hypervisor_pin_vcpu",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580021476,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:12",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580075540,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580122852,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580168308,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580216244,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580283412,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580266932,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580271940,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580423364,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580645956,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580912756,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580998404,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581094548,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:24",
      "file": "kernel/smp.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:24",
      "file": "kernel/smp.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:24",
      "file": "kernel/smp.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:24",
      "file": "kernel/smp.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580185044,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580132532,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580176516,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hypervisor_pin_vcpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580228708,
      "name": "hypervisor_pin_vcpu",
      "external": false,
      "loc": "include/linux/hypervisor.h:15",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu_callback",
        "kernel/smp.c:smp_call_on_cpu_callback"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void hypervisor_pin_vcpu(int cpu)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void hypervisor_pin_vcpu(int cpu)
```
</details>
</li>
</ul>
