# Function: <code>apic_is_x2apic_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool apic_is_x2apic_enabled()
```

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579356838,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:108",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic"
      ]
    },
    {
      "addr": 18446744071595040771,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:108",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595044304,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:108",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207087,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:108",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212181,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:108",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579213693,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:108",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584341489,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:108",
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
      "addr": 18446744071579356838,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool apic_is_x2apic_enabled()
```

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579363714,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:113",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071595206505,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:113",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595210232,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:113",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207902,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:113",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212821,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:113",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579214413,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:113",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584689605,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:113",
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
      "addr": 18446744071579363714,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool apic_is_x2apic_enabled()
```

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579381785,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071595449392,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595453249,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219566,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224533,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226013,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584876165,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:112",
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
      "addr": 18446744071579381785,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool apic_is_x2apic_enabled()
```

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579201288,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071596370471,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596374092,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217348,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222245,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579223059,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584964831,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:111",
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
      "addr": 18446744071579201288,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool apic_is_x2apic_enabled()
```

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579216757,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071602688840,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602692599,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579235037,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579238309,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579239811,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585386127,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
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
      "addr": 18446744071579216757,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool apic_is_x2apic_enabled()
```

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579228581,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071602860692,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602864057,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247597,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251061,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579252323,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579298131,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585628942,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
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
      "addr": 18446744071579228581,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool apic_is_x2apic_enabled()
```

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579252277,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071604657629,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604660994,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271405,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274613,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579276131,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579322739,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756142,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:121",
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
      "addr": 18446744071579252277,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool apic_is_x2apic_enabled()
```

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579266229,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071604755575,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604759024,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285725,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288985,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579290547,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579338040,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    },
    {
      "addr": 18446744071585929798,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585987917,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
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
      "addr": 18446744071579266229,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579338040,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool apic_is_x2apic_enabled()
```

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579039760,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579267877,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071604769083,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604772549,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288478,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579294873,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579296531,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579342216,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    },
    {
      "addr": 18446744071586072934,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586134925,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
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
      "addr": 18446744071579267877,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579342216,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579049782,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579295793,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609114945,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609119143,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317940,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:__irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324677,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579326336,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371828,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586820564,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "drivers/iommu/amd/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888586,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
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
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591243605,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591259545,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612179711,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612183878,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326261,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579327936,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591264781,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586938730,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
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
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591187249,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591202460,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614320164,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614324189,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614338918,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328981,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579330624,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591206983,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586822573,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592050433,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592073456,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615248780,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615253056,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615266949,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383765,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579385776,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592080214,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587382717,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593816962,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593840031,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617025539,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617030105,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617042883,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449091,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451571,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593847446,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588692836,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627549913,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627656853,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627662252,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627667482,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627675092,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579536675,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539155,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627699251,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590171658,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:120",
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
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619296393,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619413797,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619419212,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619424448,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619436058,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579549523,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579551971,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619456995,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590485882,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
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
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621589869,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621709397,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621713926,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621720480,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621728666,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579577523,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579579747,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621753299,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590831868,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:110",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool apic_is_x2apic_enabled()
```

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579040112,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579266581,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071604695362,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698845,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287182,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579290681,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579292339,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579338120,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    },
    {
      "addr": 18446744071585834054,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585895293,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
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
      "addr": 18446744071579266581,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579338120,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578972969,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579202237,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604662841,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604666263,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222412,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579225909,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579228022,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270558,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585694642,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585755029,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool apic_is_x2apic_enabled()
```

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579039696,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579267781,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071604772946,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604776412,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288382,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579291881,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579293539,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579338040,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    },
    {
      "addr": 18446744071586022950,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586084941,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
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
      "addr": 18446744071579267781,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579338040,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool apic_is_x2apic_enabled()
```

```json
{
  "name": "apic_is_x2apic_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579043360,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579273381,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ]
    },
    {
      "addr": 18446744071604773224,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604776690,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294270,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579300713,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302371,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579346488,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ]
    },
    {
      "addr": 18446744071586130902,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586193229,
      "name": "apic_is_x2apic_enabled",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:122",
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
      "addr": 18446744071579273381,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579346488,
      "name": "apic_is_x2apic_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool apic_is_x2apic_enabled()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool apic_is_x2apic_enabled()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool apic_is_x2apic_enabled()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool apic_is_x2apic_enabled()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool apic_is_x2apic_enabled()
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
bool apic_is_x2apic_enabled()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
