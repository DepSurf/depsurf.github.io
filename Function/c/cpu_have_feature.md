# Function: <code>cpu_have_feature</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool cpu_have_feature(unsigned int num)
```

```json
{
  "name": "cpu_have_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490261208,
      "name": "cpu_have_feature",
      "external": true,
      "loc": "arch/arm64/kernel/cpufeature.c:2048",
      "file": "arch/arm64/kernel/cpufeature.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cpufeature.c:verify_local_elf_hwcaps"
      ],
      "caller_func": [
        "arch/arm64/kernel/fpsimd.c:fpsimd_init",
        "arch/arm64/kernel/fpsimd.c:fpsimd_init",
        "arch/arm64/kernel/process.c:__switch_to",
        "arch/arm64/kernel/cpuinfo.c:c_show",
        "drivers/base/cpu.c:print_cpu_modalias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490259776,
      "name": "cpu_have_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
  "name": "cpu_have_feature",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231564728,
      "name": "cpu_have_feature",
      "external": false,
      "loc": "arch/arm/include/asm/cpufeature.h:30",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpu_modalias"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "cpu_have_feature",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292155800,
      "name": "cpu_have_feature",
      "external": false,
      "loc": "arch/powerpc/include/asm/cpufeature.h:28",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpu_modalias"
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
bool cpu_have_feature(unsigned int num)
```
</details>
</li>
</ul>
