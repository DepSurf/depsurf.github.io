# Function: <code>platform_device_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584405888,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:201",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/dwc2/pci.c:dwc2_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584405888,
      "name": "platform_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584744554,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:221",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584741296,
      "name": "platform_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584934570,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:236",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584931312,
      "name": "platform_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585019164,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:236",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015840,
      "name": "platform_device_put",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585441484,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:236",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585438160,
      "name": "platform_device_put",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585684540,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:235",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681296,
      "name": "platform_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585814713,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:236",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585811424,
      "name": "platform_device_put",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586048137,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:274",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044848,
      "name": "platform_device_put",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586196233,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:351",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586192656,
      "name": "platform_device_put",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586958793,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:412",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586953328,
      "name": "platform_device_put",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587044537,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:564",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587038512,
      "name": "platform_device_put",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586928361,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:563",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586922320,
      "name": "platform_device_put",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587490809,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:543",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/firmware/sysfb.c:sysfb_init",
        "drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587484720,
      "name": "platform_device_put",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588813580,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:548",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/firmware/sysfb.c:sysfb_init",
        "drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588806832,
      "name": "platform_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590311884,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:548",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/dax/hmem/device.c:hmem_register_device",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/firmware/sysfb.c:sysfb_init",
        "drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590304368,
      "name": "platform_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590632364,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:548",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/firmware/sysfb.c:sysfb_init",
        "drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590624816,
      "name": "platform_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590991596,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:549",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/firmware/sysfb.c:sysfb_init",
        "drivers/firmware/sysfb_simplefb.c:sysfb_create_simplefb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590984064,
      "name": "platform_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498996800,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:351",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/acpi/arm64/iort.c:iort_add_platform_device",
        "drivers/soc/imx/gpcv2.c:imx_gpcv2_probe",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_of_xlate",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/ethernet/freescale/fman/mac.c:mac_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/of/platform.c:of_platform_device_create_pdata",
        "drivers/of/platform.c:of_device_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498991576,
      "name": "platform_device_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231564200,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:351",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "arch/arm/mach-omap2/omap_device.c:omap_device_build",
        "arch/arm/mach-omap2/hsmmc.c:omap_hsmmc_init",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_clk_probe",
        "drivers/soc/imx/gpc.c:imx_gpc_probe",
        "drivers/soc/imx/gpcv2.c:imx_gpcv2_probe",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_of_xlate",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/dwc2/pci.c:dwc2_pci_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/of/platform.c:of_platform_device_create_pdata",
        "drivers/of/platform.c:of_device_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231559988,
      "name": "platform_device_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292154244,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:351",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:add_pcspkr",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/of/platform.c:of_platform_device_create_pdata",
        "drivers/of/platform.c:of_device_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292146160,
      "name": "platform_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276370846,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:351",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/of/platform.c:of_platform_device_create_pdata",
        "drivers/of/platform.c:of_device_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276366180,
      "name": "platform_device_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585956441,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:351",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585952864,
      "name": "platform_device_put",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585805657,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:351",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585802080,
      "name": "platform_device_put",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586146249,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:351",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586142672,
      "name": "platform_device_put",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void platform_device_put(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586254953,
      "name": "platform_device_put",
      "external": true,
      "loc": "drivers/base/platform.c:351",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586251360,
      "name": "platform_device_put",
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
