# Function: <code>platform_device_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584408672,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:229",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/base/platform.c:__platform_create_bundle",
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
      "addr": 18446744071584408672,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584744032,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:249",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
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
      "addr": 18446744071584744032,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584934048,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:264",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
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
      "addr": 18446744071584934048,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585018672,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:264",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
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
      "addr": 18446744071585018672,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585440992,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:264",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi",
        "drivers/acpi/apei/hest.c:hest_parse_ghes",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
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
      "addr": 18446744071585440992,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585684048,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:263",
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
      "addr": 18446744071585684048,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585814192,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:264",
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
      "addr": 18446744071585814192,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586047552,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:302",
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
      "addr": 18446744071586047552,
      "name": "platform_device_alloc",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586195632,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:379",
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
      "addr": 18446744071586195632,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586956272,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:440",
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
      "addr": 18446744071586956272,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587041312,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:592",
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
      "addr": 18446744071587041312,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586925120,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:591",
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
      "addr": 18446744071586925120,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587487536,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:571",
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
      "addr": 18446744071587487536,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588810016,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:576",
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
      "addr": 18446744071588810016,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590308016,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:576",
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
      "addr": 18446744071590308016,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590628464,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:576",
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
      "addr": 18446744071590628464,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590987680,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:577",
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
      "addr": 18446744071590987680,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498995808,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:379",
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
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/net/ethernet/freescale/fman/mac.c:mac_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/of/platform.c:of_device_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498995808,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231563652,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:379",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/omap_device.c:omap_device_build",
        "arch/arm/mach-omap2/hsmmc.c:omap_hsmmc_init",
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_clk_probe",
        "drivers/soc/imx/gpc.c:imx_gpc_probe",
        "drivers/soc/imx/gpcv2.c:imx_gpcv2_probe",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/dwc2/pci.c:dwc2_pci_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/of/platform.c:of_device_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231563652,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292153392,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:379",
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
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/of/platform.c:of_device_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292153392,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276370310,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:379",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/ipmi/ipmi_plat_data.c:ipmi_platform_add",
        "drivers/regulator/dummy.c:regulator_dummy_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/of/platform.c:of_device_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276370310,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585955840,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:379",
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
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585955840,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805056,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:379",
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
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805056,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586145648,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:379",
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
      "addr": 18446744071586145648,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct platform_device * platform_device_alloc(const char * name, int id)
```

```json
{
  "name": "platform_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586254352,
      "name": "platform_device_alloc",
      "external": true,
      "loc": "drivers/base/platform.c:379",
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
      "addr": 18446744071586254352,
      "name": "platform_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
