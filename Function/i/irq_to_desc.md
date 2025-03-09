# Function: <code>irq_to_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579738000,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:111",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_irqs"
      ],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:setup_vector_irq",
        "arch/x86/kernel/apic/vector.c:setup_vector_irq",
        "arch/x86/kernel/apic/vector.c:setup_vector_irq",
        "arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:request_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:free_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738000,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579761318,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:133",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc"
      ],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:setup_vector_irq",
        "arch/x86/kernel/apic/vector.c:setup_vector_irq",
        "arch/x86/kernel/apic/vector.c:setup_vector_irq",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest",
        "kernel/irq/manage.c:request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759696,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579788342,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:309",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:setup_vector_irq",
        "arch/x86/kernel/apic/vector.c:setup_vector_irq",
        "arch/x86/kernel/apic/vector.c:setup_vector_irq",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest",
        "kernel/irq/manage.c:request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785872,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579785878,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:321",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:setup_vector_irq",
        "arch/x86/kernel/apic/vector.c:setup_vector_irq",
        "arch/x86/kernel/apic/vector.c:setup_vector_irq",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783328,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579819254,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:319",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816704,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579853109,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:336",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850432,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579900101,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:336",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897424,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579934917,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932240,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985045,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982368,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580033173,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:per_cpu_count_show"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:disable_hardirq",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:misrouted_irq",
        "kernel/irq/spurious.c:misrouted_irq",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029904,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580014053,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:irq_check_status_bit",
        "kernel/irq/manage.c:irq_has_action",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:disable_hardirq",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:misrouted_irq",
        "kernel/irq/spurious.c:misrouted_irq",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016240,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580017598,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs",
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:irq_check_status_bit",
        "kernel/irq/manage.c:irq_has_action",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:disable_hardirq",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016896,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580149842,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs",
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:irq_check_status_bit",
        "kernel/irq/manage.c:irq_has_action",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:disable_hardirq",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149120,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580294699,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq_safe",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:irq_check_status_bit",
        "kernel/irq/manage.c:irq_has_action",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:disable_hardirq",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irq_sim.c:irq_sim_handle_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293552,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580505693,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:354",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq_safe",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:irq_check_status_bit",
        "kernel/irq/manage.c:irq_has_action",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:disable_hardirq",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irq_sim.c:irq_sim_handle_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504192,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580577837,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:379",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq_safe",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:irq_check_status_bit",
        "kernel/irq/manage.c:irq_has_action",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:disable_hardirq",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/resend.c:check_irq_resend",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irq_sim.c:irq_sim_handle_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576272,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580642189,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:379",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq_safe",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:irq_check_status_bit",
        "kernel/irq/manage.c:irq_has_action",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:disable_hardirq",
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/resend.c:check_irq_resend",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irq_sim.c:irq_sim_handle_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580640560,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491172264,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/arm64/kernel/machine_kexec.c:machine_crash_shutdown",
        "arch/arm64/kernel/machine_kexec.c:machine_crash_shutdown",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_phys_irq",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/irqchip/irq-gic.c:gic_irq_domain_map",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_teardown",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_setup",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc",
        "drivers/irqchip/irq-partition-percpu.c:partition_create_desc",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_unmask_leg_irq",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_mask_leg_irq",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_unmask_intx_irq",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_mask_intx_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/perf/arm_pmu.c:arm_perf_starting_cpu",
        "drivers/perf/arm_pmu.c:armpmu_request_irq",
        "drivers/perf/arm_pmu.c:armpmu_free_irq",
        "drivers/perf/arm_pmu_platform.c:pmu_parse_irqs",
        "drivers/perf/arm_pmu_platform.c:pmu_parse_irqs",
        "drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting",
        "drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491168312,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225197184,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/arm/kernel/machine_kexec.c:machine_crash_shutdown",
        "arch/arm/kernel/machine_kexec.c:machine_crash_shutdown",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/irqchip/irq-hip04.c:hip04_irq_domain_map",
        "drivers/irqchip/irq-gic.c:gic_irq_domain_map",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_teardown",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_setup",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc",
        "drivers/irqchip/irq-partition-percpu.c:partition_create_desc",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_domain_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/perf/arm_pmu.c:arm_perf_starting_cpu",
        "drivers/perf/arm_pmu.c:armpmu_request_irq",
        "drivers/perf/arm_pmu.c:armpmu_free_irq",
        "drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe",
        "drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225194144,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284071668,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/powerpc/kernel/eeh_driver.c:eeh_set_irq_state",
        "arch/powerpc/kernel/machine_kexec.c:machine_kexec_mask_interrupts",
        "arch/powerpc/kernel/machine_kexec.c:machine_kexec_mask_interrupts",
        "arch/powerpc/sysdev/xics/xics-common.c:xics_migrate_irqs_away",
        "arch/powerpc/sysdev/xics/xics-common.c:xics_migrate_irqs_away",
        "arch/powerpc/sysdev/xics/xics-common.c:xics_migrate_irqs_away",
        "arch/powerpc/sysdev/xive/common.c:xive_scan_interrupts",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/resend.c:resend_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284067152,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271723852,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271720720,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579953781,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951104,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579891653,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irq_sim.c:irq_sim_handle_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888992,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579945317,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942640,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct irq_desc * irq_to_desc(unsigned int irq)
```

```json
{
  "name": "irq_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579991669,
      "name": "irq_to_desc",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:351",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:init_IRQ",
        "arch/x86/kernel/topology.c:arch_register_cpu",
        "arch/x86/kernel/apic/vector.c:lapic_online",
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:free_percpu_nmi",
        "kernel/irq/manage.c:free_percpu_irq",
        "kernel/irq/manage.c:remove_percpu_irq",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread_dtor",
        "kernel/irq/manage.c:set_irq_wake_real",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:irq_can_set_affinity_usr",
        "kernel/irq/manage.c:irq_can_set_affinity",
        "kernel/irq/manage.c:synchronize_irq",
        "kernel/irq/manage.c:synchronize_hardirq",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:irq_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:init_irq_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/irq/proc.c:irq_node_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_list_proc_show",
        "kernel/irq/proc.c:irq_effective_aff_proc_show",
        "kernel/irq/proc.c:irq_affinity_list_proc_show",
        "kernel/irq/proc.c:irq_affinity_proc_show",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/msi.c:free_msi_irqs",
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989024,
      "name": "irq_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
