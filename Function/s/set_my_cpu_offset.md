# Function: <code>set_my_cpu_offset</code>

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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_my_cpu_offset(long unsigned int off)
```

```json
{
  "name": "set_my_cpu_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510816160,
      "name": "set_my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:14",
      "file": "arch/arm64/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/setup.c:smp_setup_processor_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490271280,
      "name": "set_my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:14",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:secondary_start_kernel"
      ],
      "caller_func": [
        "arch/arm64/kernel/smp.c:smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490269296,
      "name": "set_my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_my_cpu_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243263088,
      "name": "set_my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:13",
      "file": "arch/arm/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/setup.c:smp_setup_processor_id",
        "arch/arm/kernel/setup.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243269232,
      "name": "set_my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:13",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp.c:smp_prepare_boot_cpu"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void set_my_cpu_offset(long unsigned int off)
```
</details>
</li>
</ul>
