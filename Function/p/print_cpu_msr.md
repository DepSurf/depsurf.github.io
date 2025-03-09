# Function: <code>print_cpu_msr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void print_cpu_msr(struct cpuinfo_x86 * c)
```

```json
{
  "name": "print_cpu_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579111229,
      "name": "print_cpu_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1128",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:print_cpu_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111328,
      "name": "print_cpu_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void print_cpu_msr(struct cpuinfo_x86 * c)
```

```json
{
  "name": "print_cpu_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579111005,
      "name": "print_cpu_msr",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1247",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:print_cpu_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111104,
      "name": "print_cpu_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void print_cpu_msr(struct cpuinfo_x86 * c)
```
</details>
</li>
</ul>
