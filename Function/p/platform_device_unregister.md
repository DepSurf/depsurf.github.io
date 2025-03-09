# Function: <code>platform_device_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584407024,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:455",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/usb/phy/phy-generic.c:usb_phy_generic_unregister",
        "drivers/usb/dwc2/pci.c:dwc2_pci_remove",
        "drivers/input/serio/i8042.c:i8042_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407024,
      "name": "platform_device_unregister",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584744801,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:475",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/input/serio/i8042.c:i8042_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742400,
      "name": "platform_device_unregister",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584934817,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:489",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/input/serio/i8042.c:i8042_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584932416,
      "name": "platform_device_unregister",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585018272,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:489",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/input/serio/i8042.c:i8042_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585018272,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585440592,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:489",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/input/serio/i8042.c:i8042_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585440592,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585683296,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:488",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/input/serio/i8042.c:i8042_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585683296,
      "name": "platform_device_unregister",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585813440,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:488",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/wm8350-core.c:wm8350_device_exit",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813440,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586046800,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:528",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046800,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586194752,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:606",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586194752,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586956672,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:667",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/tty/serial/kgdboc.c:exit_kgdboc",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586956992,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587041712,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:819",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/tty/serial/kgdboc.c:exit_kgdboc",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587042000,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586925521,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:818",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/tty/serial/kgdboc.c:exit_kgdboc",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586925824,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587488161,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:782",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/tty/serial/kgdboc.c:exit_kgdboc",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587488480,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588810664,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:791",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/video/fbdev/core/fbmem.c:do_remove_conflicting_framebuffers",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/tty/serial/kgdboc.c:exit_kgdboc",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/firmware/sysfb.c:sysfb_disable",
        "drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588811024,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590308696,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:791",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/video/aperture.c:aperture_detach_platform_device",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/tty/serial/kgdboc.c:exit_kgdboc",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/firmware/sysfb.c:sysfb_disable",
        "drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590309104,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590629192,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:791",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/video/aperture.c:aperture_detach_platform_device",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/tty/serial/kgdboc.c:exit_kgdboc",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/firmware/sysfb.c:sysfb_disable",
        "drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590629600,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590988424,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:791",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/video/aperture.c:aperture_detach_platform_device",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/tty/serial/kgdboc.c:exit_kgdboc",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/firmware/sysfb.c:sysfb_disable",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590988832,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498994920,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:606",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/bus/hisi_lpc.c:hisi_lpc_acpi_remove_subdev",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/firmware/raspberrypi.c:rpi_firmware_remove",
        "drivers/firmware/raspberrypi.c:rpi_firmware_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498994920,
      "name": "platform_device_unregister",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231563092,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:606",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "fs/pstore/ram.c:ramoops_exit",
        "fs/pstore/ram.c:ramoops_init",
        "fs/pstore/ram.c:ramoops_init",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/sm501.c:sm501_dev_remove",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_remove_child",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_probe",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_probe",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_probe",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/phy/phy-generic.c:usb_phy_generic_unregister",
        "drivers/usb/dwc2/pci.c:dwc2_pci_remove",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "sound/soc/soc-utils.c:snd_soc_util_exit",
        "sound/soc/soc-utils.c:snd_soc_util_init",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231563092,
      "name": "platform_device_unregister",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292151280,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:606",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/input/serio/i8042.c:i8042_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292151280,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276369706,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:606",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/edac/sifive_edac.c:sifive_edac_exit",
        "drivers/edac/sifive_edac.c:sifive_edac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276369706,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585954960,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:606",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585954960,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585804176,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:606",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585804176,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586144768,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:606",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586144768,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void platform_device_unregister(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586253456,
      "name": "platform_device_unregister",
      "external": true,
      "loc": "drivers/base/platform.c:606",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/apei/hest.c:hest_ghes_dev_register",
        "drivers/virtio/virtio_mmio.c:vm_unregister_cmdline_device",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_exit",
        "drivers/char/tpm/tpm_tis.c:cleanup_tis",
        "drivers/char/tpm/tpm_tis.c:init_tis",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/ezx-pcap.c:pcap_remove_subdev",
        "drivers/mfd/da903x.c:__remove_subdev",
        "drivers/mfd/adp5520.c:__remove_subdev",
        "drivers/mfd/tps6586x.c:__remove_subdev",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/eisa/virtual_root.c:virtual_eisa_root_init",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586253456,
      "name": "platform_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
