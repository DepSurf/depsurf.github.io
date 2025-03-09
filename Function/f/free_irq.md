# Function: <code>free_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579744592,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1552",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_notify",
        "kernel/irq/devres.c:devm_irq_release",
        "kernel/irq/devres.c:devm_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_free_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_free_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_del_irq_chip",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/tps65912-irq.c:tps65912_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_exit",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_free_irq",
        "drivers/usb/host/xhci.c:xhci_free_irq",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579744592,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579767392,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1582",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_free_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_free_vectors",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_free_irq",
        "drivers/usb/host/xhci.c:xhci_free_irq",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579767392,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579794384,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1582",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_free_irq",
        "drivers/usb/host/xhci.c:xhci_free_irq",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794384,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791424,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1627",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791424,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824928,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1680",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824928,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579858096,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1724",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/aer.c:aer_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_remove_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858096,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905648,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1740",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_remove_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_remove",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905648,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1861",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_remove_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/twl6030-irq.c:twl6030_exit_irq",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948829,
      "name": "free_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579941856,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992032,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1853",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_remove_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/twl6030-irq.c:twl6030_exit_irq",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992032,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580047520,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1892",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_remove",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:ec_remove_handlers",
        "drivers/acpi/evged.c:ged_shutdown",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/serial/8250/8250_core.c:serial_unlink_irq_chain",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/intel/dmar.c:free_iommu",
        "drivers/iommu/intel/dmar.c:free_iommu",
        "drivers/iommu/intel/svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_free_interrupt",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_setup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047520,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030720,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1962",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:ec_remove_handlers",
        "drivers/acpi/evged.c:ged_shutdown",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_find_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/serial/8250/8250_core.c:serial_unlink_irq_chain",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/intel/dmar.c:free_iommu",
        "drivers/iommu/intel/dmar.c:free_iommu",
        "drivers/iommu/intel/svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_free_interrupt",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_setup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030720,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580031456,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1963",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/evged.c:ged_shutdown",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel/svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_free_interrupt",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031456,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163968,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1992",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/evged.c:ged_shutdown",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel/svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_free_interrupt",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163968,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580310160,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:2026",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib-cdev.c:lineevent_free",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_stop",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/evged.c:ged_shutdown",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe",
        "drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_ioctl_common",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel/svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_free_interrupt",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580310160,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580522992,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:2018",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib-cdev.c:lineevent_free",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_stop",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:ec_remove_handlers",
        "drivers/acpi/evged.c:ged_shutdown",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe",
        "drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_ioctl_common",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel/svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580522992,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580595920,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:2024",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib-cdev.c:lineevent_free",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_stop",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:ec_remove_handlers",
        "drivers/acpi/evged.c:ged_shutdown",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe",
        "drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_ioctl_common",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel/svm.c:intel_svm_finish_prq",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_unregister",
        "drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580595920,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660336,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:2021",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib-cdev.c:lineevent_free",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_stop",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:ec_remove_handlers",
        "drivers/acpi/evged.c:ged_shutdown",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe",
        "drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_ioctl_common",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel/svm.c:intel_svm_finish_prq",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_unregister",
        "drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/input/serio/i8042.c:i8042_setup_aux",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660336,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491182008,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1853",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_teardown",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_remove_interrupt_handler",
        "drivers/acpi/evged.c:ged_shutdown",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources",
        "drivers/soc/fsl/qbman/bman.c:bman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/amba-pl011.c:sbsa_uart_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/meson_uart.c:meson_uart_shutdown",
        "drivers/tty/serial/msm_serial.c:msm_shutdown",
        "drivers/tty/serial/owl-uart.c:owl_uart_shutdown",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/twl6030-irq.c:twl6030_exit_irq",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_stop",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_remove",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/clocksource/timer-of.c:timer_of_cleanup",
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_shutdown",
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe",
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe",
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_remove",
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_remove",
        "drivers/perf/arm-cci.c:pmu_free_irq",
        "drivers/perf/arm_pmu.c:armpmu_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491182008,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225205400,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1853",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/bus/omap_l3_smx.c:omap3_l3_remove",
        "drivers/bus/omap_l3_smx.c:omap3_l3_remove",
        "drivers/bus/omap_l3_smx.c:omap3_l3_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_teardown",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_put_resources",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_remove",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/amba-pl011.c:sbsa_uart_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/meson_uart.c:meson_uart_shutdown",
        "drivers/tty/serial/msm_serial.c:msm_shutdown",
        "drivers/tty/serial/omap-serial.c:serial_omap_shutdown",
        "drivers/tty/serial/owl-uart.c:owl_uart_shutdown",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/twl6030-irq.c:twl6030_exit_irq",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/musb/musb_core.c:musb_free",
        "drivers/rtc/rtc-pl031.c:pl031_remove",
        "drivers/mmc/host/sdhci.c:sdhci_remove_host",
        "drivers/mmc/host/sdhci.c:__sdhci_add_host",
        "drivers/mmc/host/sdhci.c:sdhci_suspend_host",
        "drivers/clocksource/timer-of.c:timer_of_cleanup",
        "drivers/clocksource/dw_apb_timer.c:dw_apb_clockevent_stop",
        "drivers/clocksource/timer-tegra.c:tegra_init_timer",
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_remove",
        "drivers/memory/omap-gpmc.c:gpmc_remove",
        "drivers/perf/arm-cci.c:pmu_free_irq",
        "drivers/perf/arm_pmu.c:armpmu_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225205400,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284083712,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1853",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_shutdown",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/twl6030-irq.c:twl6030_exit_irq",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284083712,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271728726,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1853",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/perf_event.c:release_pmc_hardware",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sifive.c:sifive_serial_remove",
        "drivers/tty/serial/sifive.c:sifive_serial_probe",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/twl6030-irq.c:twl6030_exit_irq",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/mmc/host/of_mmc_spi.c:of_mmc_spi_exit",
        "drivers/clocksource/timer-of.c:timer_of_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271728726,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579960768,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1853",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_remove_interrupt_handler",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960768,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898608,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1853",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_remove_interrupt_handler",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898608,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952304,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1853",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_remove_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/twl6030-irq.c:twl6030_exit_irq",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952304,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
const void * free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998688,
      "name": "free_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1853",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_dead",
        "kernel/irq/devres.c:devm_free_irq",
        "kernel/irq/devres.c:devm_irq_release",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/osl.c:acpi_os_remove_interrupt_handler",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/pnp/resource.c:pnp_check_irq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/char/hpet.c:hpet_release",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/intel-svm.c:intel_svm_finish_prq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq",
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_free_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_exit",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_exit",
        "drivers/mfd/twl6030-irq.c:twl6030_exit_irq",
        "drivers/mfd/da9052-irq.c:da9052_free_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8997-irq.c:max8997_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/max8998-irq.c:max8998_irq_exit",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/input/serio/i8042.c:i8042_free_irqs",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998688,
      "name": "free_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>const void *</code>
</li>
</ul>
</details>
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
