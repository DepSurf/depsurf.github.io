# Function: <code>system_uses_irq_prio_masking</code>

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
bool system_uses_irq_prio_masking()
```

```json
{
  "name": "system_uses_irq_prio_masking",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490179900,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kernel/debug-monitors.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/debug-monitors.c:send_user_sigtrap",
        "arch/arm64/kernel/debug-monitors.c:mdscr_write",
        "arch/arm64/kernel/debug-monitors.c:mdscr_write",
        "arch/arm64/kernel/debug-monitors.c:mdscr_write",
        "arch/arm64/kernel/debug-monitors.c:mdscr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490184548,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kernel/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/irq.c:init_IRQ",
        "arch/arm64/kernel/irq.c:init_IRQ"
      ]
    },
    {
      "addr": 18446603336490193848,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/process.c:copy_thread_tls",
        "arch/arm64/kernel/process.c:cpu_do_idle"
      ],
      "caller_func": [
        "arch/arm64/kernel/process.c:__show_regs"
      ]
    },
    {
      "addr": 18446603336490219212,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/setup.c:setup_arch"
      ]
    },
    {
      "addr": 18446603336490234540,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/signal.c:do_notify_resume",
        "arch/arm64/kernel/signal.c:do_notify_resume",
        "arch/arm64/kernel/signal.c:do_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490244496,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/traps.c:bad_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490271420,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:secondary_start_kernel",
        "arch/arm64/kernel/smp.c:secondary_start_kernel"
      ],
      "caller_func": [
        "arch/arm64/kernel/smp.c:smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446603336490277184,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kernel/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490315164,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kernel/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/suspend.c:cpu_suspend",
        "arch/arm64/kernel/suspend.c:cpu_suspend",
        "arch/arm64/kernel/suspend.c:cpu_suspend",
        "arch/arm64/kernel/suspend.c:cpu_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490325020,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kernel/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/acpi.c:apei_claim_sea",
        "arch/arm64/kernel/acpi.c:apei_claim_sea",
        "arch/arm64/kernel/acpi.c:apei_claim_sea",
        "arch/arm64/kernel/acpi.c:apei_claim_sea"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490327292,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kernel/machine_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/machine_kexec.c:machine_kexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503951032,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kernel/sdei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/sdei.c:__sdei_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490340840,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/fault.c:debug_exception_exit",
        "arch/arm64/mm/fault.c:debug_exception_enter",
        "arch/arm64/mm/fault.c:do_sp_pc_abort",
        "arch/arm64/mm/fault.c:do_el0_ia_bp_hardening"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490446348,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503978864,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "arch/arm64/kvm/hyp/switch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/hyp/switch.c:__kvm_vcpu_run_nvhe",
        "arch/arm64/kvm/hyp/switch.c:__kvm_vcpu_run_nvhe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493955328,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493970056,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496378776,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init",
        "drivers/irqchip/irq-gic-v3.c:gic_handle_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_handle_irq"
      ],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases"
      ]
    },
    {
      "addr": 18446603336498229788,
      "name": "system_uses_irq_prio_masking",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:604",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:xen_debug_interrupt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496372792,
      "name": "system_uses_irq_prio_masking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336490184548,
      "name": "system_uses_irq_prio_masking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336490192080,
      "name": "system_uses_irq_prio_masking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336490219212,
      "name": "system_uses_irq_prio_masking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336490269792,
      "name": "system_uses_irq_prio_masking",
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
bool system_uses_irq_prio_masking()
```
</details>
</li>
</ul>
