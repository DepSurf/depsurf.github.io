# Function: <code>dev_err_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_err_probe(const struct device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "dev_err_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_err_probe",
      "external": true,
      "loc": "drivers/base/core.c:4401",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_rs485_mode",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591485642,
      "name": "dev_err_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587005472,
      "name": "dev_err_probe",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_err_probe(const struct device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "dev_err_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_err_probe",
      "external": true,
      "loc": "drivers/base/core.c:4628",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_rs485_mode",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/opp/core.c:_add_opp_table_indexed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591429224,
      "name": "dev_err_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586888112,
      "name": "dev_err_probe",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_err_probe(const struct device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "dev_err_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_err_probe",
      "external": true,
      "loc": "drivers/base/core.c:4693",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_rs485_mode",
        "drivers/base/core.c:device_links_check_suppliers",
        "drivers/base/core.c:device_links_check_suppliers",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/opp/core.c:_add_opp_table_indexed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592487385,
      "name": "dev_err_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587449664,
      "name": "dev_err_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int dev_err_probe(const struct device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "dev_err_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_err_probe",
      "external": true,
      "loc": "drivers/base/core.c:4732",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_rs485_mode",
        "drivers/base/core.c:device_links_check_suppliers",
        "drivers/base/core.c:device_links_check_suppliers",
        "drivers/base/platform.c:platform_get_irq_byname",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594356892,
      "name": "dev_err_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588767424,
      "name": "dev_err_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int dev_err_probe(const struct device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "dev_err_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590260720,
      "name": "dev_err_probe",
      "external": true,
      "loc": "drivers/base/core.c:4951",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/tty/serial/serial_core.c:uart_get_rs485_mode",
        "drivers/tty/serial/max310x.c:max310x_i2c_probe",
        "drivers/base/core.c:device_links_check_suppliers",
        "drivers/base/core.c:device_links_check_suppliers",
        "drivers/base/platform.c:platform_get_irq_byname",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590260720,
      "name": "dev_err_probe",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int dev_err_probe(const struct device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "dev_err_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590579984,
      "name": "dev_err_probe",
      "external": true,
      "loc": "drivers/base/core.c:4956",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_of_phy_optional_get",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/tty/serial/serial_core.c:uart_get_rs485_mode",
        "drivers/tty/serial/serial_core.c:uart_get_rs485_mode",
        "drivers/tty/serial/max310x.c:max310x_i2c_probe",
        "drivers/base/core.c:device_links_check_suppliers",
        "drivers/base/core.c:device_links_check_suppliers",
        "drivers/base/platform.c:platform_get_irq_byname",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590579984,
      "name": "dev_err_probe",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int dev_err_probe(const struct device * dev, int err, const char * fmt, void (anon))
```

```json
{
  "name": "dev_err_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590937872,
      "name": "dev_err_probe",
      "external": true,
      "loc": "drivers/base/core.c:4970",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_of_phy_optional_get",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/tty/serial/serial_core.c:uart_get_rs485_mode",
        "drivers/tty/serial/serial_core.c:uart_get_rs485_mode",
        "drivers/tty/serial/max310x.c:max310x_i2c_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/max310x.c:max310x_set_ref_clk",
        "drivers/base/core.c:device_links_check_suppliers",
        "drivers/base/core.c:device_links_check_suppliers",
        "drivers/base/platform.c:platform_get_irq_byname",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590937872,
      "name": "dev_err_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int dev_err_probe(const struct device * dev, int err, const char * fmt, void (anon))
```
</details>
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
