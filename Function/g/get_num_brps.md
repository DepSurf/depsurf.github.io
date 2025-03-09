# Function: <code>get_num_brps</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "get_num_brps",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510824228,
      "name": "get_num_brps",
      "external": false,
      "loc": "arch/arm64/include/asm/hw_breakpoint.h:140",
      "file": "arch/arm64/kernel/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/hw_breakpoint.c:arch_hw_breakpoint_init",
        "arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490501424,
      "name": "get_num_brps",
      "external": false,
      "loc": "arch/arm64/include/asm/hw_breakpoint.h:140",
      "file": "arch/arm64/kvm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/debug.c:kvm_arm_clear_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490502192,
      "name": "get_num_brps",
      "external": false,
      "loc": "arch/arm64/include/asm/hw_breakpoint.h:140",
      "file": "arch/arm64/kvm/reset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int get_num_brps()
```

```json
{
  "name": "get_num_brps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224463852,
      "name": "get_num_brps",
      "external": false,
      "loc": "arch/arm/kernel/hw_breakpoint.c:212",
      "file": "arch/arm/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init",
        "arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224463852,
      "name": "get_num_brps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int get_num_brps()
```
</details>
</li>
</ul>
