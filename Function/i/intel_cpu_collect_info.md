# Function: <code>intel_cpu_collect_info</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int intel_cpu_collect_info(struct ucode_cpu_info * uci)
```

```json
{
  "name": "intel_cpu_collect_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579249968,
      "name": "intel_cpu_collect_info",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel.c:187",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249968,
      "name": "intel_cpu_collect_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int intel_cpu_collect_info(struct ucode_cpu_info * uci)
```

```json
{
  "name": "intel_cpu_collect_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579310992,
      "name": "intel_cpu_collect_info",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel.c:187",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310992,
      "name": "intel_cpu_collect_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int intel_cpu_collect_info(struct ucode_cpu_info * uci)
```

```json
{
  "name": "intel_cpu_collect_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579318144,
      "name": "intel_cpu_collect_info",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel.c:187",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318144,
      "name": "intel_cpu_collect_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int intel_cpu_collect_info(struct ucode_cpu_info * uci)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int intel_cpu_collect_info(struct ucode_cpu_info * uci)
```
</details>
</li>
</ul>
