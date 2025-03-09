# Function: <code>disable_irq_nosync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741888,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:462",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741888,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579764048,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:476",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764048,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791008,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:476",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791008,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788704,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:447",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788704,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822160,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:475",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822160,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855936,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:508",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855936,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579902896,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:511",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902896,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579949272,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:540",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937680,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579997499,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:533",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987808,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580044763,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:609",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036576,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580027963,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:679",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019824,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580028683,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:679",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020464,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580161163,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:703",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152240,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580307116,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:718",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297968,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580519660,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:710",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/acpi/ec.c:acpi_ec_mask_events",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580509856,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580592588,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:713",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/acpi/ec.c:acpi_ec_mask_events",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581984,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580657068,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:715",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/acpi/ec.c:acpi_ec_mask_events",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646336,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491188496,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:533",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/video/fbdev/mx3fb.c:mx3fb_dma_done",
        "drivers/video/fbdev/mx3fb.c:mx3fb_dma_done",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/thermal/armada_thermal.c:armada_overheat_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491175664,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225211220,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:533",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "drivers/video/fbdev/mx3fb.c:mx3fb_dma_done",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mtd/nand/raw/omap2.c:omap_nand_irq",
        "drivers/mtd/nand/raw/omap2.c:omap_nand_irq",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_interrupt",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_tx_interrupt",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_irq",
        "drivers/thermal/armada_thermal.c:armada_overheat_isr",
        "drivers/clocksource/timer-tegra.c:tegra_timer_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225201036,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284092024,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:533",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/powerpc/kernel/eeh_driver.c:eeh_set_irq_state",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_shutdown",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_event",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_int_handler",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284077552,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271734976,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:533",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271727022,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579966235,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:533",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956544,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579904075,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:533",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894400,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579957771,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:533",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948080,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void disable_irq_nosync(unsigned int irq)
```

```json
{
  "name": "disable_irq_nosync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580004155,
      "name": "disable_irq_nosync",
      "external": true,
      "loc": "kernel/irq/manage.c:533",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:free_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_disable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/da903x.c:da903x_irq_handler",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq_nosync",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994512,
      "name": "disable_irq_nosync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
