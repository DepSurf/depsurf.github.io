# Function: <code>__pci_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583272256,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1278",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/gpio/gpio-intel-mid.c:intel_gpio_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_pci_module_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/usb/dwc2/pci.c:dwc2_pci_driver_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583272256,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583583232,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1275",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_pci_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init",
        "drivers/platform/x86/intel_pmc_core.c:intel_pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583583232,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720320,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1284",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init",
        "drivers/platform/x86/intel_pmc_core.c:intel_pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720320,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583761184,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1302",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init",
        "drivers/platform/x86/intel_pmc_core.c:intel_pmc_core_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761184,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020560,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1370",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020560,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584217392,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1391",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584217392,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584307008,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1388",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307008,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584502000,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1422",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584502000,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584638000,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1435",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584638000,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585320832,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1400",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585320832,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585474160,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1379",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474160,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585354032,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1379",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354032,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585813136,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1392",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813136,
      "name": "__pci_register_driver",
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587002448,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1421",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587002448,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588171616,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1427",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/tty/serial/8250/8250_mid.c:mid8250_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171616,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588447648,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1428",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/tty/serial/8250/8250_mid.c:mid8250_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447648,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588744592,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1440",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_mid.c:mid8250_pci_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744592,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496884328,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1435",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496884328,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230161100,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1435",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/mfd/sm501.c:sm501_base_init",
        "drivers/usb/dwc2/pci.c:dwc2_pci_driver_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230161100,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290969024,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1435",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/video/fbdev/gxt4500.c:gxt4500_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290969024,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275581308,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1435",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275581308,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584590160,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1435",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/nvme/host/pci.c:nvme_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590160,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584518288,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1435",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/nvme/host/pci.c:nvme_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584518288,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584588160,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1435",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584588160,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __pci_register_driver(struct pci_driver * drv, struct module * owner, const char * mod_name)
```

```json
{
  "name": "__pci_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584696064,
      "name": "__pci_register_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1435",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init",
        "drivers/xen/platform-pci.c:platform_driver_init",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_init",
        "drivers/char/agp/via-agp.c:agp_via_init",
        "drivers/ata/ata_piix.c:piix_init",
        "drivers/ata/pata_sis.c:sis_pci_driver_init",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_init",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_init",
        "drivers/usb/host/ohci-pci.c:ohci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-pci.c:xhci_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584696064,
      "name": "__pci_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
