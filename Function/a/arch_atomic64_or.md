# Function: <code>arch_atomic64_or</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_or",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589258817,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:247",
      "file": "kernel/locking/mutex.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_or",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589499493,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/mutex.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589962234,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579862727,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590189898,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579911439,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591206401,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:218",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579955425,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:218",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591701577,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:218",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579943549,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:218",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591643384,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:218",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579951298,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:218",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592817002,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:218",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580079999,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:218",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594721577,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:218",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594727311,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:218",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596471807,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:218",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596478848,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:218",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597012697,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:137",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597020966,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:137",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597942041,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:137",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597950310,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:137",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void arch_atomic64_or(long int i, atomic64_t * v)
```

```json
{
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490185892,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:fpsimd_flush_cpu_state",
        "arch/arm64/kernel/fpsimd.c:fpsimd_thread_switch",
        "arch/arm64/kernel/fpsimd.c:sve_probe_vqs",
        "arch/arm64/kernel/fpsimd.c:sve_set_vector_length",
        "arch/arm64/kernel/fpsimd.c:sve_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490195016,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/process.c:set_tagged_addr_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490215372,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:sve_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490229792,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490236336,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/stacktrace.c:unwind_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490254500,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/kernel/cpuinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cpuinfo.c:__cpuinfo_store_cpu",
        "arch/arm64/kernel/cpuinfo.c:__cpuinfo_store_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490262168,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/kernel/cpufeature.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cpufeature.c:update_cpu_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490276204,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/smp.c:smp_prepare_cpus",
        "arch/arm64/kernel/smp.c:smp_init_cpus"
      ]
    },
    {
      "addr": 18446603336510827440,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/kernel/acpi_numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/acpi_numa.c:acpi_numa_gicc_affinity_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490336308,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/kernel/ssbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set",
        "arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set",
        "arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set",
        "arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set",
        "arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490361212,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/numa.c:numa_update_cpu"
      ],
      "caller_func": [
        "arch/arm64/mm/numa.c:numa_add_memblk",
        "arch/arm64/mm/numa.c:node_set_online"
      ]
    },
    {
      "addr": 18446603336490393456,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:hardware_enable_nolock",
        "virt/kvm/kvm_main.c:kvm_vcpu_check_block",
        "virt/kvm/kvm_main.c:mark_page_dirty_in_slot",
        "virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490435908,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_vcpu_init",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_vcpu_init",
        "virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_set_mpstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490476960,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "virt/kvm/arm/psci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/psci.c:kvm_hvc_call_handler",
        "virt/kvm/arm/psci.c:kvm_psci_0_2_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490505556,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/kvm/sys_regs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/sys_regs.c:reset_sys_reg_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490528192,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm64/kvm/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp",
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490538120,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "virt/kvm/arm/vgic/vgic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic.c:vgic_kick_vcpus",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate",
        "virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock",
        "virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490551200,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "virt/kvm/arm/vgic/vgic-v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_doorbell_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490611204,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "virt/kvm/arm/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/pmu.c:kvm_pmu_set_counter_event_type",
        "virt/kvm/arm/pmu.c:kvm_pmu_perf_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510843836,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "arch/arm/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/xen/enlighten.c:fdt_find_hyper_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490632828,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490639788,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:add_taint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490654684,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:notify_cpu_starting"
      ],
      "caller_func": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:boot_cpu_init"
      ]
    },
    {
      "addr": 18446603336490668760,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490709308,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490738940,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:calculate_sigpending",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490787020,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__arm64_sys_prctl",
        "kernel/sys.c:__arm64_sys_prctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510877780,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490845536,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490930756,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ]
    },
    {
      "addr": 18446603336490940820,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490992612,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balance_enter_idle",
        "kernel/sched/fair.c:task_numa_placement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491002312,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_online_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491019368,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491048716,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491050976,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_clear",
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491058056,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503932308,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491113972,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491172712,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    },
    {
      "addr": 18446603336491185476,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:irq_set_thread_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491193892,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:check_irq_resend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491202484,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491209992,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_map_generic_chip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491237964,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491255840,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491306004,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491416644,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491425268,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_oneshot_notify",
        "kernel/time/tick-sched.c:tick_clock_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491486560,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:flush_module_icache",
        "kernel/module.c:flush_module_icache"
      ],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    },
    {
      "addr": 18446603336491501512,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491543996,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create"
      ]
    },
    {
      "addr": 18446603336491583988,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491586388,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_leave_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491605804,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag",
        "kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446603336491669760,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491769160,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491789408,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491847784,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:trace_rb_cpu_prepare",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491890848,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_line",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_filter_add_remove_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491933604,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491971112,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:event_enable_count_probe",
        "kernel/trace/trace_events.c:event_enable_probe",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:trace_event_enable_tgid_record",
        "kernel/trace/trace_events.c:trace_event_enable_cmd_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491980256,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491999752,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger",
        "kernel/trace/trace_events_trigger.c:update_cond_flag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492310712,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492389876,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_cpu",
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492395332,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492399160,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492418596,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:handler_chain",
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_dup_mmap",
        "kernel/events/uprobes.c:uprobe_dup_mmap",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/events/uprobes.c:uprobe_munmap",
        "kernel/events/uprobes.c:register_for_each_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492435108,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__arm64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492445612,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:wait_on_page_bit_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492481216,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:mark_oom_victim",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492490648,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492498508,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__writepage",
        "mm/page-writeback.c:__writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492512820,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:__do_page_cache_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492519536,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:lru_add_drain_all",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492534924,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492567728,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492603392,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_lock",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510944452,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492638472,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_register_va",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492655148,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    },
    {
      "addr": 18446603336492712812,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492716512,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492786428,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492819808,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492857472,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:steal_suitable_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503919004,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492910988,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:swap_slot_free_notify"
      ],
      "caller_func": [
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write"
      ]
    },
    {
      "addr": 18446603336492917980,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:init_swap_address_space",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492928300,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:reuse_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492952268,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_load",
        "mm/frontswap.c:__frontswap_store",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492959512,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492998944,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:nr_hugepages_store_common",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493024244,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_to_str",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446603336493047904,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:__ksm_enter",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493059216,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:get_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503906672,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:get_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493117528,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493124260,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:single_hugepage_flag_store",
        "mm/huge_memory.c:enabled_store",
        "mm/huge_memory.c:enabled_store"
      ],
      "caller_func": [
        "mm/huge_memory.c:setup_transparent_hugepage",
        "mm/huge_memory.c:setup_transparent_hugepage"
      ]
    },
    {
      "addr": 18446603336493161220,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493218036,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:memcg_set_shrinker_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493238180,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:me_pagecache_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493253708,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493270688,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493273896,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493307796,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493357956,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493566620,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493609256,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:move_expired_inodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493628004,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493669148,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:init_page_buffers",
        "fs/buffer.c:init_page_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:mark_buffer_async_write",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493697908,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:blkdev_get_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493720744,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493806072,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493850788,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493864672,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493871876,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493895316,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/crypto/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/bio.c:__fscrypt_decrypt_bio",
        "fs/crypto/bio.c:__fscrypt_decrypt_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493906296,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:verify_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493961536,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493976044,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494000992,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_set_range_uptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494024616,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_acquire",
        "fs/quota/dquot.c:dquot_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494083140,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_coredump_filter_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494129400,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494221960,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494231708,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494235288,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494240616,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494307292,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494312388,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494337192,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_prepare_inline_data",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494387936,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async",
        "fs/ext4/inode.c:_ext4_get_block"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/inode.c:ext4_getblk"
      ]
    },
    {
      "addr": 18446603336494401708,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    },
    {
      "addr": 18446603336494432428,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494450564,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494456880,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494484716,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494497892,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494501472,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494509584,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:bclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494583856,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/super.c:ext4_set_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494641132,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494647600,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494664068,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494672792,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    },
    {
      "addr": 18446603336494680392,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494687356,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494714000,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    },
    {
      "addr": 18446603336494726696,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494734548,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494736088,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494744488,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ramfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ramfs/inode.c:ramfs_get_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494750416,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494762544,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494780124,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_mirror_bhs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494796844,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494834352,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_readpage",
        "fs/ecryptfs/mmap.c:ecryptfs_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494835368,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494895564,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:request_wait_answer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494901932,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_symlink_readpage",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494934352,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_readpages_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494959520,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:parse_dirplusfile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495061048,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/gc.c:key_schedule_gc_links"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495063448,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:__key_instantiate_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495094428,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495383080,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_write_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495581672,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495590520,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:ima_post_create_tmpfile",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495614804,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495795884,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495867988,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "block/blk-mq.c:blk_mq_hctx_mark_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495885460,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495981340,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496054008,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496102964,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496326844,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496348096,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496358468,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_queue_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511073320,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496399492,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496405456,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/irqchip/irq-partition-percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496411228,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/irqchip/irq-bcm7038-l1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496426204,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/irqchip/irq-mvebu-sei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_cp_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496429996,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/irqchip/qcom-irq-combiner.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/qcom-irq-combiner.c:combiner_irq_chip_unmask_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496433508,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/irqchip/irq-meson-gpio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496442092,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/irqchip/irq-ti-sci-inta.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496595776,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pinctrl/bcm/pinctrl-bcm2835.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496640692,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pinctrl/qcom/pinctrl-msm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496731160,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_hog",
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiod_configure_flags",
        "drivers/gpio/gpiolib.c:gpiochip_enable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:gpiod_get_direction"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_configure_flags"
      ]
    },
    {
      "addr": 18446603336496739384,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/gpio/gpiolib-legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496748888,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496809584,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_device_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496827548,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pci/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pci/remove.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497081472,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497095608,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pci/controller/pcie-cadence-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_map_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497113096,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pci/controller/pcie-rcar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497115964,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pci/controller/pcie-xilinx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497125272,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pci/controller/pci-xgene-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497128108,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pci/controller/pcie-iproc-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497134928,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pci/controller/pcie-altera-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497141808,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pci/controller/pcie-rockchip-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497151292,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pci/controller/pcie-mobiveil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_irq_msi_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497165804,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497217136,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_request_mport_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497283524,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497366840,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/video/fbdev/mx3fb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497441788,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_stop"
      ]
    },
    {
      "addr": 18446603336511118972,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497477856,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/numa.c:acpi_numa_memory_affinity_init"
      ]
    },
    {
      "addr": 18446603336497642288,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497652880,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:initiator_cmp",
        "drivers/acpi/hmat/hmat.c:initiator_cmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497660296,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/acpi/battery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497663324,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511140824,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:of_clk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498009452,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_get_any_slave_channel",
        "drivers/dma/dmaengine.c:dma_get_slave_channel",
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498030288,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/dma/amba-pl08x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/amba-pl08x.c:pl08x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498038528,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/dma/bcm2835-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_probe",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_probe",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_probe",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498049888,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/dma/mv_xor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe"
      ]
    },
    {
      "addr": 18446603336498057756,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/dma/mv_xor_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498061984,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/dma/mxs-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_probe"
      ]
    },
    {
      "addr": 18446603336498075716,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/dma/ipu/ipu_idmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe"
      ]
    },
    {
      "addr": 18446603336498089944,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/soc/fsl/qbman/bman_portal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498091464,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/soc/fsl/qbman/qman_portal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498095052,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/soc/fsl/qbman/bman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman.c:bman_create_affine_portal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498112336,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/soc/fsl/qbman/qman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman.c:qman_create_affine_portal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498136600,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/soc/qcom/rpmh-rsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498198340,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498204044,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498228676,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:evtchn_2l_unmask",
        "drivers/xen/events/events_2l.c:evtchn_2l_mask",
        "drivers/xen/events/events_2l.c:evtchn_2l_set_pending",
        "drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498233544,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_mask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498275212,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498309460,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_balance_voltage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498358528,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_kopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498377300,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498395940,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_throttle_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498398508,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498409268,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_open",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_port.c:tty_port_hangup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498413164,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498420420,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_open",
        "drivers/tty/pty.c:pty_open",
        "drivers/tty/pty.c:pty_set_lock",
        "drivers/tty/pty.c:pty_unthrottle",
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/pty.c:pty_close",
        "drivers/tty/pty.c:pty_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498431956,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498461936,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498548640,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498592096,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498632508,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/amba-pl011.c:pl011_dma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498649728,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498718336,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_open",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498750636,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/char/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/misc.c:misc_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498902412,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/iommu/arm-smmu-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498962848,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499021572,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499108356,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499174088,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499200060,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks",
        "drivers/base/arch_topology.c:update_siblings_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499403972,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499414416,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_locked",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499441144,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499458924,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499471172,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499477128,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:alloc_dax",
        "drivers/dax/super.c:alloc_dax",
        "drivers/dax/super.c:run_dax",
        "drivers/dax/super.c:dax_write_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499488832,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499533716,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_check_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499589252,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported",
        "drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported",
        "drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached",
        "drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported",
        "drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported",
        "drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499736320,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499979816,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500004404,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/net/ethernet/broadcom/bgmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500029340,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_close",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500093048,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_close",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500125224,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500156248,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500219036,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:usb_remove_device",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500235728,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ]
    },
    {
      "addr": 18446603336500295020,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_default_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500299724,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:claimintf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500338240,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500388556,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500499580,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control"
      ]
    },
    {
      "addr": 18446603336500534208,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init"
      ]
    },
    {
      "addr": 18446603336500554108,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_pci_resume",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_resume",
        "drivers/usb/host/uhci-hcd.c:start_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init"
      ]
    },
    {
      "addr": 18446603336500582168,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500633768,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500668876,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500699144,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/usb/host/xhci-mtk-sch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500759272,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/input/mousedev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/mousedev.c:mousedev_event",
        "drivers/input/mousedev.c:mousedev_event",
        "drivers/input/mousedev.c:mousedev_event",
        "drivers/input/mousedev.c:mousedev_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500785476,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500796828,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/input/misc/uinput.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500889924,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/i2c/busses/i2c-sprd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500895340,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500959612,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/power/supply/power_supply_hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500991496,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501033104,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_write",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:watchdog_ping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501041928,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/watchdog/rtd119x_wdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501097920,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_wakeup_thread",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:add_bound_rdev"
      ],
      "caller_func": [
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:consistency_policy_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:recovery_start_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_90_validate",
        "drivers/md/md.c:super_90_validate",
        "drivers/md/md.c:super_90_validate",
        "drivers/md/md.c:super_90_validate",
        "drivers/md/md.c:super_90_validate",
        "drivers/md/md.c:super_90_validate",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush"
      ]
    },
    {
      "addr": 18446603336501138160,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_write_all",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:end_bitmap_write",
        "drivers/md/md-bitmap.c:write_page",
        "drivers/md/md-bitmap.c:write_page",
        "drivers/md/md-bitmap.c:write_page",
        "drivers/md/md-bitmap.c:write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501159128,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_lock_for_deletion",
        "drivers/md/dm.c:dm_lock_for_deletion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501207216,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:dec_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501214812,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501276392,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501278056,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus",
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501302756,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501464240,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_blink_setup",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501476940,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/firmware/arm_sdei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_sdei.c:sdei_event_handler",
        "drivers/firmware/arm_sdei.c:sdei_event_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501500596,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/firmware/ti_sci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/ti_sci.c:ti_sci_get_free_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501522092,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/driver.c:scmi_xfer_get_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501538836,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:parse_efi_cmdline"
      ]
    },
    {
      "addr": 18446603336511283292,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/firmware/efi/memattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memattr.c:efi_memattr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511284952,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:__efi_memmap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511287652,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/firmware/efi/secureboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/secureboot.c:efi_set_secure_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501563220,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/firmware/efi/arm-init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/arm-init.c:uefi_init",
        "drivers/firmware/efi/arm-init.c:uefi_init"
      ]
    },
    {
      "addr": 18446603336511289764,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/firmware/efi/arm-runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501590948,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501597388,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_alias_get_alias_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501616252,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/of/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/platform.c:of_platform_populate",
        "drivers/of/platform.c:of_platform_bus_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501627304,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/of/dynamic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/dynamic.c:of_changeset_destroy",
        "drivers/of/dynamic.c:__of_node_dup",
        "drivers/of/dynamic.c:__of_node_dup",
        "drivers/of/dynamic.c:__of_prop_dup",
        "drivers/of/dynamic.c:__of_detach_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501633292,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/of/fdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/fdt.c:__unflatten_device_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511308104,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/of/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/irq.c:of_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501655676,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/of/overlay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/overlay.c:dup_and_fixup_symbol_prop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511310352,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/of/of_numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/of_numa.c:of_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501763420,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci_pmu_event_init",
        "drivers/perf/arm-cci.c:cci5xx_pmu_write_counters",
        "drivers/perf/arm-cci.c:__cci_pmu_enable_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501778484,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/perf/arm_pmu_platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu_platform.c:pmu_parse_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501779956,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/perf/arm_pmu_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501783128,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/perf/hisilicon/hisi_uncore_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_online_cpu",
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_get_event_idx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501788268,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_get_event_idx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501795860,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/perf/qcom_l2_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu",
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_event_add",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_event_add"
      ],
      "caller_func": [
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu"
      ]
    },
    {
      "addr": 18446603336501799072,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/perf/qcom_l3_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_offline_cpu",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501806692,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "drivers/perf/xgene_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu",
        "drivers/perf/xgene_pmu.c:xgene_perf_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501833024,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__arm64_sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501872004,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:proto_register",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501937720,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:datagram_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501941676,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501975556,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501998000,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:init_dummy_netdev",
        "net/core/dev.c:init_dummy_netdev",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:dev_alloc_name_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502097868,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_proc_update",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502261892,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/core/net-sysfs.c:show_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502278164,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502414664,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502452392,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502551596,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502693136,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp.c:tcp_poll",
        "net/ipv4/tcp.c:tcp_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502747720,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502878104,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_req_delete",
        "net/ipv4/arp.c:arp_req_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502909824,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:inet_set_link_af",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503049392,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503083432,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503205348,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_poll",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_accept",
        "net/unix/af_unix.c:unix_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503278932,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward"
      ]
    },
    {
      "addr": 18446603336503404300,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511347616,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503734436,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/dns_resolver/dns_query.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dns_resolver/dns_query.c:dns_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503749952,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503765920,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503886844,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:65",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490276204,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336490361064,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336490646048,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336490893520,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336491172712,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336491472080,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336491532304,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336491599872,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336492543816,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336492647144,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336492857976,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336492908216,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336493006368,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336493122352,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336494341512,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336494392488,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336494668216,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336494695144,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336496707920,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336497432616,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336497477856,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336498049888,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336498061984,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336498075716,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336500232448,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336500451632,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336500512376,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336500548920,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336501061352,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336501538836,
      "name": "arch_atomic64_or.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336501563220,
      "name": "arch_atomic64_or.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446603336501792040,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336503264192,
      "name": "arch_atomic64_or",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589792186,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579883551,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589514666,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579818515,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590235594,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579871711,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
  "name": "arch_atomic64_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590285478,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579917218,
      "name": "arch_atomic64_or",
      "external": false,
      "loc": "arch/x86/include/asm/atomic64_64.h:211",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void arch_atomic64_or(long int i, atomic64_t * v)
```
</details>
</li>
</ul>
