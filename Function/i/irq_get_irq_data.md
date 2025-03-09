# Function: <code>irq_get_irq_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579753248,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:161",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/hpet.c:hpet_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/pci/htirq.c:fetch_ht_irq_msg",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753248,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775792,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:161",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/pci/htirq.c:fetch_ht_irq_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/acpi/pci_link.c:acpi_irq_get_penalty",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775792,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802608,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:160",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/pci/htirq.c:fetch_ht_irq_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802608,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579799824,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:160",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/pci/htirq.c:fetch_ht_irq_msg",
        "drivers/pci/htirq.c:write_ht_irq_msg",
        "drivers/acpi/sleep.c:acpi_freeze_wake",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/i2c/i2c-core-base.c:i2c_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579799824,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579833712,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:160",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/acpi/sleep.c:acpi_s2idle_wake",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579833712,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867568,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867568,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914592,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914592,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952192,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952192,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002048,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002048,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051328,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_remove_irq",
        "kernel/irq/irqdomain.c:irq_domain_insert_irq",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irqs",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:restore_cpu_ipis",
        "drivers/xen/events/events_base.c:restore_cpu_virqs",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/iommu/intel/dmar.c:dmar_msi_read",
        "drivers/iommu/intel/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051328,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580033968,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_trim_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_remove_irq",
        "kernel/irq/irqdomain.c:irq_domain_insert_irq",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irqs",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:restore_cpu_ipis",
        "drivers/xen/events/events_base.c:restore_cpu_virqs",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/iommu/intel/dmar.c:dmar_msi_read",
        "drivers/iommu/intel/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033968,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034864,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irqs",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/iommu/intel/dmar.c:dmar_msi_read",
        "drivers/iommu/intel/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034864,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167392,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/msi.c:msi_mode_show",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irqs",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_needs_eoi_flag",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/iommu/intel/dmar.c:dmar_msi_read",
        "drivers/iommu/intel/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167392,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580314032,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:155",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_free_irq",
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by",
        "drivers/pci/msi/msi.c:pci_irq_get_affinity",
        "drivers/pci/msi/msi.c:pci_restore_msi_state",
        "drivers/pci/msi/msi.c:pci_write_msi_msg",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_needs_eoi_flag",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/iommu/intel/dmar.c:dmar_msi_read",
        "drivers/iommu/intel/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314032,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527744,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:155",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_free_irq",
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate_locked",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/pci/msi/api.c:pci_irq_get_affinity",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:pci_write_msi_msg",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_needs_eoi_flag",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/iommu/intel/dmar.c:dmar_msi_read",
        "drivers/iommu/intel/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527744,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580600800,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:155",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_free_irq",
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate_locked",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/pci/msi/api.c:pci_irq_get_affinity",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:pci_write_msi_msg",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_needs_eoi_flag",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/iommu/intel/dmar.c:dmar_msi_read",
        "drivers/iommu/intel/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580600800,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580665312,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:155",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_free_irq",
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate_locked",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by",
        "drivers/pci/msi/api.c:pci_irq_get_affinity",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:pci_write_msi_msg",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:irq_evtchn_from_virq",
        "drivers/xen/events/events_base.c:evtchn_to_info",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/iommu/intel/dmar.c:dmar_msi_read",
        "drivers/iommu/intel/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580665312,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491195824,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init",
        "virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/irqchip/irq-mbigen.c:mbigen_write_msg",
        "drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_irq_domain_free",
        "drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg",
        "drivers/irqchip/qcom-irq-combiner.c:combiner_irq_unmap",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/gpio/gpio-davinci.c:keystone_gpio_get_irq_chip",
        "drivers/gpio/gpio-davinci.c:davinci_gpio_get_irq_chip",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_map",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_teardown_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_status",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources",
        "drivers/of/irq.c:of_irq_to_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491195824,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225216436,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-imx/irq-common.c:mxc_set_irq_fiq",
        "arch/arm/mach-imx/irq-common.c:mxc_set_irq_fiq",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/irqchip/exynos-combiner.c:combiner_set_affinity",
        "drivers/irqchip/exynos-combiner.c:combiner_set_affinity",
        "drivers/irqchip/exynos-combiner.c:combiner_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_resume",
        "drivers/irqchip/irq-armada-370-xp.c:armada_xp_mpic_reenable_percpu",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_disable_force",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_disable_force",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_enable_force",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_enable_force",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/pci/controller/pci-tegra.c:tegra_msi_teardown_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_teardown_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_status",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources",
        "drivers/of/irq.c:of_irq_to_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225216436,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284098800,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/irq.c:virq_to_hw",
        "arch/powerpc/kernel/eeh_driver.c:eeh_set_irq_state",
        "arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority",
        "arch/powerpc/sysdev/mpic.c:mpic_host_map",
        "arch/powerpc/sysdev/mpic.c:mpic_set_vector",
        "arch/powerpc/sysdev/xive/common.c:xive_irq_domain_unmap",
        "arch/powerpc/sysdev/xive/common.c:xive_irq_domain_unmap",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources",
        "drivers/of/irq.c:of_irq_to_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284098800,
      "name": "irq_get_irq_data",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271739194,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources",
        "drivers/of/irq.c:of_irq_to_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271739194,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970784,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/xen/events/events_base.c:xen_shutdown_pirqs",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970784,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908608,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908608,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962320,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962320,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct irq_data * irq_get_irq_data(unsigned int irq)
```

```json
{
  "name": "irq_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008784,
      "name": "irq_get_irq_data",
      "external": true,
      "loc": "kernel/irq/chip.c:158",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irq_data",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/msi.c:get_cached_msi_msg",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get",
        "drivers/pci/msi.c:msi_mode_show",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_write_msi_msg",
        "drivers/pci/msi.c:default_restore_msi_irq",
        "drivers/pci/msi.c:arch_teardown_msi_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/iommu/dmar.c:dmar_msi_read",
        "drivers/iommu/dmar.c:dmar_msi_write",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008784,
      "name": "irq_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
