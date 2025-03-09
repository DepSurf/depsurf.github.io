# Function: <code>pm_runtime_put_noidle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583153459,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:70",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583211397,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:70",
      "file": "drivers/gpio/gpio-intel-mid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-intel-mid.c:intel_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583278873,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:70",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584447404,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:70",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585186650,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:70",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585217554,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:70",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585266642,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:70",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585539075,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:70",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585963066,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:70",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585965921,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:70",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579780231,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:75",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583450003,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:75",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583589945,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:75",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584783727,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:75",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585578788,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:75",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585612025,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:75",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585662311,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:75",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585932851,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:75",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586368522,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:75",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586371345,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:75",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579807015,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583577747,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583727097,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584907389,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584974264,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__rpm_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585330650,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585766436,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585799561,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585850007,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586121203,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586573272,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580177,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579804671,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583619355,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583767977,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584992534,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585057672,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__rpm_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585416869,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585855030,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585887746,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585938673,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586209569,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344863,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586702552,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586706124,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579838735,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583865467,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584027790,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585414422,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585480504,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__rpm_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585846840,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586294930,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586328258,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586380497,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586672881,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586809327,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586810120,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587187322,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587190913,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587305860,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579872527,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584062853,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584224894,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585657149,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585726982,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__rpm_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586094968,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586395644,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586549745,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586582623,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586636526,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586938275,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587083010,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587083662,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587483498,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587491173,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587607859,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579919567,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584147797,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584314542,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585534027,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585789319,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585859686,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__rpm_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586241000,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586537594,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586698593,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586731551,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586785646,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587095703,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587242450,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587244350,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587663610,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587671317,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587736115,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:74",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579957850,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584341831,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584509438,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585755572,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586020671,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586096269,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586484798,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586783654,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586956422,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586988955,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587044012,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587360551,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587510814,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587511992,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587945803,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587949604,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588022921,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580007706,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584476519,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584645470,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585897828,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586168074,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586243821,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586632590,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586930039,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587155110,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587188027,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587244412,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587562471,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587713951,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587715112,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588151803,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588155600,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588230379,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pm_runtime_put_noidle(struct device * dev)
```

```json
{
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580057677,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585136330,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585328798,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586171618,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586634212,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586928082,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587012253,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587428696,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587724560,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    },
    {
      "addr": 18446744071588002486,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588037086,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588096272,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588583840,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588585820,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589016195,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589020112,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589105106,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:78",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587724560,
      "name": "pm_runtime_put_noidle",
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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pm_runtime_put_noidle(struct device * dev)
```

```json
{
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040029,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585287610,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585482078,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586290210,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586743236,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587011966,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587094071,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__rpm_put_suppliers",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591519338,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587783968,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    },
    {
      "addr": 18446744071587806952,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/spi/spi-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588055190,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588085966,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588138240,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607328,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588609260,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589025747,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589029920,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591615430,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587783968,
      "name": "pm_runtime_put_noidle",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pm_runtime_put_noidle(struct device * dev)
```

```json
{
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040893,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585171306,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585361678,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164002,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586626836,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586895254,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586980279,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__rpm_put_suppliers",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587160235,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591461236,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663248,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_set_cs_timing",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    },
    {
      "addr": 18446744071587686472,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/spi/spi-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587929561,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587938006,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587968766,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588020336,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588493811,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588494252,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588912739,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588917200,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591558517,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:103",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587663248,
      "name": "pm_runtime_put_noidle",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pm_runtime_put_noidle(struct device * dev)
```

```json
{
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580173469,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585625002,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585821006,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586666258,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587173444,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587457095,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587543831,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_runtime_release_supplier",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592525816,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588251968,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    },
    {
      "addr": 18446744071588276566,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/spi/spi-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588539625,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588548443,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588580238,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588636405,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588892408,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_free_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589162435,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589162972,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589619327,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589624078,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592679127,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:106",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588251968,
      "name": "pm_runtime_put_noidle",
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580319492,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586784308,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587011545,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587936851,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588485712,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588776022,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_release_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588877746,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__rpm_put_suppliers",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594397488,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589648145,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589659324,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/spi/spi-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589859509,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589948865,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589958521,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589992140,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590052614,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590321035,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_free_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590615409,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590616090,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591117605,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591123095,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594564508,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:136",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580533684,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587917396,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588181513,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589294419,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589921744,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590268949,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_release_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590386018,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__rpm_put_suppliers",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590866692,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591263012,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_transfer_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591269420,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/spi/spi-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591532903,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591547721,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591587676,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591658500,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591947605,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_free_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592276073,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592277370,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592839557,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592845566,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592956730,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580606980,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588191428,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588457513,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589589843,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590114274,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590231008,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590589739,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_release_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590705810,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__rpm_put_suppliers",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591209876,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591617863,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_transfer_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591624236,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/spi/spi-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591954823,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591969352,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592009500,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592081348,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592370133,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_free_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592702254,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592703562,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593276181,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593282206,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593407098,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:140",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580671492,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588483428,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588754617,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589899395,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590453783,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:__uart_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590571840,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590948458,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_release_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591067666,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__rpm_put_suppliers",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591557060,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592349591,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_transfer_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592357100,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/spi/spi-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592694615,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592709192,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592749628,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592821787,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593111685,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_free_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593448294,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593449674,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594032117,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594038142,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594152810,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:138",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491204896,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496478664,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496891192,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497730880,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498615788,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/tty/serial/8250/8250_dw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dw.c:dw8250_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498621812,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/tty/serial/8250/8250_mtk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498716648,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498963976,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499060944,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499526208,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499893740,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499911348,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/spi/spi-omap2-mcspi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500012992,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500233048,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500271404,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500343100,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500711216,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500879860,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500880988,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500890196,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-sprd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501404676,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501408276,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501434176,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501684684,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225223536,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3229783064,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/bus/ti-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/ti-sysc.c:sysc_remove",
        "drivers/bus/ti-sysc.c:sysc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229791616,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3230169188,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3230555840,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231243604,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/tty/serial/8250/8250_mtk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3231343804,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3231467608,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/iommu/omap-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/omap-iommu.c:omap_iommu_attach_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3231534212,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3231616060,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 3231993016,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 3232444440,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 3232464744,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/spi/spi-omap2-mcspi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 3232535684,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232564396,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/net/ethernet/ti/davinci_mdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3232580456,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/net/ethernet/ti/cpsw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_remove",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_tx_maxrate",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_kill_vid",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_add_vid",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3232608020,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/net/ethernet/ti/cpsw_ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_ethtool_op_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 3232709424,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3232743200,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232802192,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233166240,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233179828,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/musb/musb_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_core.c:musb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3233216796,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/musb/musb_gadget.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_gadget.c:musb_gadget_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3233388576,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233389620,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233399712,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_remove",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233453048,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/power/avs/smartreflex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/avs/smartreflex.c:omap_sr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233893892,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233897796,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233924416,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3233963124,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci.c:sdhci_set_power_noreg",
        "drivers/mmc/host/sdhci.c:sdhci_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3233997764,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/host/sdhci-esdhc-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3234101272,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/clocksource/timer-ti-dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234211416,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284108496,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290686776,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290978684,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291865336,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292109656,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292236672,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292817664,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293219352,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293519796,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293567384,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293651764,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294142088,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294341852,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294344184,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294964720,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294974360,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295116592,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271745884,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275406830,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275584506,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276228836,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276344542,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276417208,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276732442,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276993724,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277149744,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277181472,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277232548,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277559682,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277670396,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277672210,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278007634,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278013810,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278038094,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278121026,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579976442,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584445271,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584595950,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585658820,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585928442,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586004029,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586323070,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586687063,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586861190,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586894107,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586950492,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587258807,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587773371,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587777168,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587842075,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579914250,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584380951,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584525758,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777578,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585853149,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164398,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586555399,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586802582,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586835227,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586891644,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586929950,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_free_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587027255,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587548405,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579967978,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584428183,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584595630,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585848228,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586118090,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586193837,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580558,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586884599,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109670,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587142587,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587198972,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587517031,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587670095,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587671256,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588106331,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588110128,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588184859,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
  "name": "pm_runtime_put_noidle",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580014602,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584534311,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584703326,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585955844,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586226698,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586302413,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586692782,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586990961,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587217174,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587250411,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587306044,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587624935,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587776479,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587777640,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588223867,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588227664,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588302723,
      "name": "pm_runtime_put_noidle",
      "external": false,
      "loc": "include/linux/pm_runtime.h:73",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void pm_runtime_put_noidle(struct device * dev)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void pm_runtime_put_noidle(struct device * dev)
```
</details>
</li>
</ul>
