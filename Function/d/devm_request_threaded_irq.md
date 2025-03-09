# Function: <code>devm_request_threaded_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758144,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:47",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single",
        "drivers/misc/bmp085.c:bmp085_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/phy/phy-generic.c:usb_phy_generic_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758144,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579781056,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:47",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781056,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807792,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:47",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807792,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805424,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:50",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805424,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579839552,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:50",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/pci/pcie/pcie-dpc.c:dpc_probe",
        "drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579839552,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579873296,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873296,
      "name": "devm_request_threaded_irq",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920336,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920336,
      "name": "devm_request_threaded_irq",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579958672,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-core.c:ata_host_activate",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958672,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008464,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008464,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580058432,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058432,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580040320,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040320,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580041168,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041168,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580173712,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173712,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580320896,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320896,
      "name": "devm_request_threaded_irq",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580535760,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580535760,
      "name": "devm_request_threaded_irq",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580609104,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609104,
      "name": "devm_request_threaded_irq",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580673616,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673616,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491206136,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/bus/fsl-mc/dprc-driver.c:dprc_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe",
        "drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_attach_dev",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init",
        "drivers/net/ethernet/freescale/fman/fman.c:read_dts_node",
        "drivers/net/ethernet/freescale/fman/fman.c:read_dts_node",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/edac/altera_edac.c:altr_edac_a10_device_add",
        "drivers/edac/altera_edac.c:altr_edac_device_probe",
        "drivers/edac/altera_edac.c:altr_edac_device_probe",
        "drivers/edac/altera_edac.c:altr_sdram_probe",
        "drivers/edac/altera_edac.c:altr_sdram_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel",
        "drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_probe",
        "drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491206136,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225224364,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/bus/omap_l3_noc.c:omap_l3_probe",
        "drivers/bus/omap_l3_noc.c:omap_l3_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_init",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/dma/ti/omap-dma.c:omap_dma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_probe",
        "drivers/iommu/omap-iommu.c:omap_iommu_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/tps65217.c:tps65217_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip",
        "drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip",
        "drivers/mtd/nand/raw/omap_elm.c:elm_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/usb/phy/phy-generic.c:usb_phy_generic_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-twl.c:twl_rtc_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe",
        "drivers/power/avs/smartreflex.c:sr_late_init",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/watchdog/npcm_wdt.c:npcm_wdt_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/clocksource/em_sti.c:em_sti_probe",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe",
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe",
        "drivers/mailbox/tegra-hsp.c:tegra_hsp_probe",
        "drivers/mailbox/tegra-hsp.c:tegra_hsp_probe",
        "drivers/memory/tegra/mc.c:tegra_mc_probe",
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225224364,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284109488,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-core.c:ata_host_activate",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284109488,
      "name": "devm_request_threaded_irq",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271746728,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271746728,
      "name": "devm_request_threaded_irq",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579977200,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977200,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915008,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915008,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579968736,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579968736,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int devm_request_threaded_irq(struct device * dev, unsigned int irq, irq_handler_t handler, irq_handler_t thread_fn, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "devm_request_threaded_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015360,
      "name": "devm_request_threaded_irq",
      "external": true,
      "loc": "kernel/irq/devres.c:51",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/dpc.c:dpc_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015360,
      "name": "devm_request_threaded_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
