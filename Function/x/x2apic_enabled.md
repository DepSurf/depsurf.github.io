# Function: <code>x2apic_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595037004,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:235",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595040757,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:235",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206961,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:235",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212141,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:235",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579213660,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:235",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584341342,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:235",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595205124,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:242",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595206467,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:242",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207777,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:242",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212781,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:242",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579214380,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:242",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584689458,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:242",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595448021,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:241",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595449354,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:241",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219441,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:241",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224493,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:241",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579225980,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:241",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584876018,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:241",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596366393,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:240",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596370433,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:240",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217217,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:240",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222205,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:240",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579223021,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:240",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584964817,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:240",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602684820,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602688802,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234945,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579238269,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579239773,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585386113,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
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
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602856257,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602860654,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247505,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251021,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579252285,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579298093,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585628810,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
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
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604653188,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604657591,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271313,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274573,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579276093,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579322701,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756010,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:257",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
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
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604752237,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:259",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604755535,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:259",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285633,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:259",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288942,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:259",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579290509,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:259",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604768563,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:259",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585929685,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:259",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585987789,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:259",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
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
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604704249,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ]
    },
    {
      "addr": 18446744071604765642,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604769043,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288385,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579294830,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579296493,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604794401,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586072821,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586134797,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579039732,
      "name": "x2apic_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int x2apic_enabled()
```

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579049748,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ]
    },
    {
      "addr": 18446744071579295759,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071609114905,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317852,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:__irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371794,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    },
    {
      "addr": 18446744071586820451,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "drivers/iommu/amd/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049748,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071579295759,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071579371794,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int x2apic_enabled()
```

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591243571,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ]
    },
    {
      "addr": 18446744071591259511,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071612179671,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591264747,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591243571,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071591259511,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071591264747,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int x2apic_enabled()
```

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591187215,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ]
    },
    {
      "addr": 18446744071591202426,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071614320124,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614338898,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591206949,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    },
    {
      "addr": 18446744071586822467,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591187215,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071591202426,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071591206949,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int x2apic_enabled()
```

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592050399,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ]
    },
    {
      "addr": 18446744071592073422,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071615248743,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615266929,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592080180,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    },
    {
      "addr": 18446744071587382611,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592050399,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071592073422,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071592080180,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int x2apic_enabled()
```

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593816924,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ]
    },
    {
      "addr": 18446744071593839993,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071617025502,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617042863,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593847408,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    },
    {
      "addr": 18446744071588692750,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:256",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593816924,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071593839993,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071593847408,
      "name": "x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627549807,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:253",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:253",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627661321,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:253",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627674654,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:253",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:253",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:253",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627699470,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:253",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590171548,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:253",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
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
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619296287,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619418281,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619435679,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619457214,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590485772,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:255",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
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
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621589420,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:231",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:231",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621713393,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:231",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621728299,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:231",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:231",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:231",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621753516,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:231",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:231",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_add"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604630537,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ]
    },
    {
      "addr": 18446744071604691921,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604695322,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287089,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579290638,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579292301,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604708343,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585833941,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585895165,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040084,
      "name": "x2apic_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604598562,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ]
    },
    {
      "addr": 18446744071604659442,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071604662801,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222338,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579225877,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579228005,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604676081,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    },
    {
      "addr": 18446744071585694547,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585754901,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972969,
      "name": "x2apic_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579202237,
      "name": "x2apic_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579270558,
      "name": "x2apic_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604708345,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ]
    },
    {
      "addr": 18446744071604769505,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604772906,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288289,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579291838,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579293501,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604785910,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586022837,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586084813,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579039668,
      "name": "x2apic_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604708361,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ]
    },
    {
      "addr": 18446744071604769762,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604773184,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294177,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579300670,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302333,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604798531,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586130789,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586193101,
      "name": "x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:264",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579043332,
      "name": "x2apic_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int x2apic_enabled()
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int x2apic_enabled()
```
</details>
</li>
</ul>
