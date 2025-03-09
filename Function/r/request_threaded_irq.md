# Function: <code>request_threaded_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579749664,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1610",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/tps65912-irq.c:tps65912_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579749664,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772000,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1640",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772000,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579798912,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1640",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_setup_msix",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798912,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579796192,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1690",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579796192,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579829936,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1747",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829936,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579863664,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1791",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863664,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910672,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1807",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910672,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1981",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949211,
      "name": "request_threaded_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579946240,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579996384,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1973",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579996384,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580043648,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:2012",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irq",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_intx",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:serial_link_irq_chain",
        "drivers/char/hpet.c:hpet_ioctl_ieon",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd.c:usb_hcd_request_irqs",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_setup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043648,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580026848,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:2082",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_intx",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:serial_link_irq_chain",
        "drivers/char/hpet.c:hpet_ioctl_ieon",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/amd/init.c:iommu_setup_intcapxt",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd.c:usb_hcd_request_irqs",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_setup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026848,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027536,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:2083",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/char/hpet.c:hpet_ioctl_ieon",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027536,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580160016,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:2112",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:serial_link_irq_chain",
        "drivers/char/hpet.c:hpet_ioctl_ieon",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580160016,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580305872,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:2146",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/char/hpet.c:hpet_ioctl_ieon",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580305872,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580518352,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:2138",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/char/hpet.c:hpet_ioctl_ieon",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518352,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580591264,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:2144",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/char/hpet.c:hpet_ioctl_ieon",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_register",
        "drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580591264,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580655552,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:2141",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/manage.c:request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/char/hpet.c:hpet_ioctl_ieon",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/amd/init.c:__iommu_setup_intcapxt",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_register",
        "drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655552,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491187112,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1973",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_init",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_alloc_chan_resources",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/soc/fsl/qbman/bman.c:bman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/tty/serial/amba-pl011.c:pl011_allocate_irq",
        "drivers/tty/serial/meson_uart.c:meson_uart_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/timer-rockchip.c:rk_timer_init",
        "drivers/clocksource/timer-owl.c:owl_timer_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_register",
        "drivers/mailbox/pl320-ipc.c:pl320_probe",
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_startup",
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe",
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe",
        "drivers/perf/arm-cci.c:cci_pmu_event_init",
        "drivers/perf/arm_pmu.c:armpmu_request_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491187112,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225210000,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1973",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "arch/arm/mach-vexpress/spc.c:ve_spc_init",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/bus/omap_l3_smx.c:omap3_l3_probe",
        "drivers/bus/omap_l3_smx.c:omap3_l3_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/serial/amba-pl011.c:pl011_allocate_irq",
        "drivers/tty/serial/meson_uart.c:meson_uart_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/rda-uart.c:rda_uart_startup",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/auxdisplay/arm-charlcd.c:charlcd_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/rtc/rtc-pl031.c:pl031_probe",
        "drivers/mmc/host/sdhci.c:__sdhci_add_host",
        "drivers/mmc/host/sdhci.c:sdhci_resume_host",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_setup",
        "drivers/clocksource/renesas-ostm.c:ostm_init",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/timer-rockchip.c:rk_timer_init",
        "drivers/clocksource/timer-tegra.c:tegra_init_timer",
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/clocksource/timer-qcom.c:msm_local_timer_starting_cpu",
        "drivers/clocksource/timer-owl.c:owl_timer_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe",
        "drivers/mailbox/pl320-ipc.c:pl320_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/perf/arm-cci.c:cci_pmu_event_init",
        "drivers/perf/arm_pmu.c:armpmu_request_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225210000,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284090192,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1973",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/smp.c:smp_request_message_ipi",
        "arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe",
        "arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe",
        "arch/powerpc/sysdev/xics/xics-common.c:xics_smp_probe",
        "arch/powerpc/sysdev/xive/common.c:xive_smp_probe",
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal-elog.c:opal_elog_init",
        "arch/powerpc/platforms/powernv/opal-dump.c:opal_platform_dump_init",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init",
        "arch/powerpc/platforms/pseries/event_sources.c:request_event_sources_irqs",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/hvc/hvsi.c:hvsi_init",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284090192,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271733976,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1973",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/perf_event.c:riscv_event_init",
        "arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/serial/sifive.c:sifive_serial_probe",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/mmc/host/of_mmc_spi.c:of_mmc_spi_init",
        "drivers/clocksource/timer-of.c:timer_of_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271733976,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965120,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1973",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965120,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579902960,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1973",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902960,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956656,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1973",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956656,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int request_threaded_irq(unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580003040,
      "name": "request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1973",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_os_install_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_add_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_request_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/da9052-irq.c:da9052_request_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580003040,
      "name": "request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
