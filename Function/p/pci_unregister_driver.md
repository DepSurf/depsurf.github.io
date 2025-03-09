# Function: <code>pci_unregister_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583272336,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1305",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/usb/dwc2/pci.c:dwc2_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583272336,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583583312,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1302",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583583312,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720400,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1311",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720400,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583761264,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1329",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761264,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020656,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1398",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020656,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224640,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1419",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_driver_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224640,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584313280,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1416",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313280,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584508208,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1450",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584508208,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584644240,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1463",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644240,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585326320,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1428",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585326320,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585479664,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1407",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585479664,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585360432,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1407",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585360432,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585819760,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1421",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819760,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587002560,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1450",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587002560,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588171744,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1456",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/tty/serial/8250/8250_mid.c:mid8250_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171744,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588447776,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1457",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/tty/serial/8250/8250_mid.c:mid8250_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447776,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588744720,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1469",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_mid.c:mid8250_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744720,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496889664,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1463",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496889664,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230161192,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1463",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/mfd/sm501.c:sm501_base_exit",
        "drivers/usb/dwc2/pci.c:dwc2_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230161192,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290969152,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1463",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/video/fbdev/gxt4500.c:gxt4500_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290969152,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275583206,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1463",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275583206,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584594720,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1463",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/nvme/host/pci.c:nvme_exit",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584594720,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584524528,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1463",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/nvme/host/pci.c:nvme_exit",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524528,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584594400,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1463",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_driver_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584594400,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void pci_unregister_driver(struct pci_driver * drv)
```

```json
{
  "name": "pci_unregister_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584696160,
      "name": "pci_unregister_driver",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:1463",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit",
        "drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_exit",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_exit",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit",
        "drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_init",
        "drivers/char/agp/intel-agp.c:agp_intel_cleanup",
        "drivers/char/agp/via-agp.c:agp_via_cleanup",
        "drivers/ata/ata_piix.c:piix_exit",
        "drivers/ata/pata_sis.c:sis_pci_driver_exit",
        "drivers/ata/ata_generic.c:ata_generic_pci_driver_exit",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_cleanup",
        "drivers/usb/host/ohci-pci.c:ohci_pci_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584696160,
      "name": "pci_unregister_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
