# Function: <code>platform_device_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584406240,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:325",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 18446744071584406240,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584741648,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:345",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 18446744071584741648,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584931664,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:360",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 18446744071584931664,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585016192,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:360",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 18446744071585016192,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585438512,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:360",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 18446744071585438512,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585681648,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:359",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 18446744071585681648,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585811792,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:360",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 18446744071585811792,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:398",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 18446744071586048443,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586045200,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:475",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 18446744071586196392,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586193008,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:536",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586959034,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586953712,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:688",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/dax/hmem/device.c:hmem_register_device",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591486687,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587038784,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:687",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/dax/hmem/device.c:hmem_register_device",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591430367,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586922592,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:651",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/dax/hmem/device.c:hmem_register_device",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/firmware/sysfb.c:sysfb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592489647,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587486080,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:656",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/dax/hmem/device.c:hmem_register_device",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/firmware/sysfb.c:sysfb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594359294,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588808240,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:656",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/dax/hmem/device.c:hmem_register_device",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/firmware/sysfb.c:sysfb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596246755,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590306144,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:656",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/firmware/sysfb.c:sysfb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596775119,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590626544,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:657",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:init_kgdboc",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/base/platform.c:platform_add_devices",
        "drivers/mfd/wm8350-core.c:wm8350_client_dev_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/firmware/sysfb.c:sysfb_init",
        "drivers/firmware/sysfb_simplefb.c:sysfb_create_simplefb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597684370,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590985792,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498992024,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:475",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/acpi/arm64/iort.c:iort_add_platform_device",
        "drivers/soc/imx/gpcv2.c:imx_gpcv2_probe",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/ethernet/freescale/fman/mac.c:mac_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498992024,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231560320,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:475",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/omap_device.c:omap_device_register",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_clk_probe",
        "drivers/soc/imx/gpc.c:imx_gpc_probe",
        "drivers/soc/imx/gpcv2.c:imx_gpcv2_probe",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/dwc2/pci.c:dwc2_pci_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231560320,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292146704,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:475",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:add_pcspkr",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 13835058055292146704,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 868
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
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276366678,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:475",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 18446743936276366678,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:475",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585956600,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585953216,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:475",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_register",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805816,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585802432,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:475",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 18446744071586146408,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586143024,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int platform_device_add(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "platform_device_add",
      "external": true,
      "loc": "drivers/base/platform.c:475",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:platform_device_register",
        "drivers/base/platform.c:platform_device_register",
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
      "addr": 18446744071586255112,
      "name": "platform_device_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586251712,
      "name": "platform_device_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
