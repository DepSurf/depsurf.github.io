# Function: <code>local_daif_mask</code>

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
void local_daif_mask()
```

```json
{
  "name": "local_daif_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490180784,
      "name": "local_daif_mask",
      "external": false,
      "loc": "arch/arm64/include/asm/daifflags.h:20",
      "file": "arch/arm64/kernel/debug-monitors.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/debug-monitors.c:mdscr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490234560,
      "name": "local_daif_mask",
      "external": false,
      "loc": "arch/arm64/include/asm/daifflags.h:20",
      "file": "arch/arm64/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/signal.c:do_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490244492,
      "name": "local_daif_mask",
      "external": false,
      "loc": "arch/arm64/include/asm/daifflags.h:20",
      "file": "arch/arm64/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/traps.c:bad_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490269944,
      "name": "local_daif_mask",
      "external": false,
      "loc": "arch/arm64/include/asm/daifflags.h:20",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/smp.c:local_cpu_stop",
        "arch/arm64/kernel/smp.c:cpu_die"
      ]
    },
    {
      "addr": 18446603336490277348,
      "name": "local_daif_mask",
      "external": false,
      "loc": "arch/arm64/include/asm/daifflags.h:20",
      "file": "arch/arm64/kernel/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490315176,
      "name": "local_daif_mask",
      "external": false,
      "loc": "arch/arm64/include/asm/daifflags.h:20",
      "file": "arch/arm64/kernel/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/suspend.c:cpu_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490327288,
      "name": "local_daif_mask",
      "external": false,
      "loc": "arch/arm64/include/asm/daifflags.h:20",
      "file": "arch/arm64/kernel/machine_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/machine_kexec.c:machine_kexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490446344,
      "name": "local_daif_mask",
      "external": false,
      "loc": "arch/arm64/include/asm/daifflags.h:20",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490269944,
      "name": "local_daif_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void local_daif_mask()
```
</details>
</li>
</ul>
