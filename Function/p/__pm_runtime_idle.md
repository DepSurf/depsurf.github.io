# Function: <code>__pm_runtime_idle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584441456,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:887",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_free",
        "drivers/gpio/gpio-intel-mid.c:intel_mid_irq_type",
        "drivers/gpio/gpio-intel-mid.c:intel_gpio_direction_input",
        "drivers/gpio/gpio-intel-mid.c:intel_gpio_direction_output",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_free",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584441456,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777392,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:887",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_free",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:spi_flash_read",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777392,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584968608,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:964",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_free",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:spi_flash_read",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584968608,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585056752,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:964",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_free",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:spi_flash_read",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585056752,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585479664,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:965",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_free",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:spi_flash_read",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585479664,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585720848,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:965",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/phy/phy-core.c:phy_pm_runtime_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_free",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_mem_exec_op",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585720848,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585852736,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:972",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/phy/phy-core.c:phy_pm_runtime_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_free",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_remove",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serdev/core.c:serdev_device_close",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585852736,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586090064,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1001",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/phy/phy-core.c:phy_pm_runtime_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_free",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_remove",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serdev/core.c:serdev_device_close",
        "drivers/base/core.c:__device_link_free_srcu",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/soundwire/bus.c:sdw_nwrite",
        "drivers/soundwire/bus.c:sdw_nread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586090064,
      "name": "__pm_runtime_idle",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586237616,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1003",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/phy/phy-core.c:phy_pm_runtime_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_free",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_remove",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serdev/core.c:serdev_device_close",
        "drivers/base/core.c:__device_link_free_srcu",
        "drivers/base/core.c:device_link_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586237616,
      "name": "__pm_runtime_idle",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587010076,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1001",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status"
      ],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "fs/debugfs/file.c:debugfs_show_regset32",
        "block/keyslot-manager.c:blk_ksm_evict_key",
        "block/keyslot-manager.c:blk_ksm_get_slot_for_key",
        "block/keyslot-manager.c:blk_ksm_get_slot_for_key",
        "block/keyslot-manager.c:blk_ksm_get_slot_for_key",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_remove",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_get_state",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_hw_is_prepared",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_exit",
        "drivers/tty/serdev/core.c:devm_serdev_device_release",
        "drivers/base/core.c:__device_link_free_srcu",
        "drivers/base/core.c:device_link_add",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/port.c:unlink_peers",
        "drivers/usb/core/port.c:unlink_peers",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004800,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587094812,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1031",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_put_suppliers"
      ],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "fs/debugfs/file.c:debugfs_show_regset32",
        "block/keyslot-manager.c:blk_ksm_evict_key",
        "block/keyslot-manager.c:blk_ksm_get_slot_for_key",
        "block/keyslot-manager.c:blk_ksm_get_slot_for_key",
        "block/keyslot-manager.c:blk_ksm_get_slot_for_key",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_remove",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_get_state",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_hw_is_prepared",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_exit",
        "drivers/tty/serdev/core.c:devm_serdev_device_release",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:__device_link_free_srcu",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_drop_link",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/port.c:unlink_peers",
        "drivers/usb/core/port.c:unlink_peers",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587089520,
      "name": "__pm_runtime_idle",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586980959,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1031",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_put_suppliers"
      ],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "fs/debugfs/file.c:debugfs_show_regset32",
        "block/keyslot-manager.c:blk_ksm_evict_key",
        "block/keyslot-manager.c:blk_ksm_evict_key",
        "block/keyslot-manager.c:blk_ksm_get_slot_for_key",
        "block/keyslot-manager.c:blk_ksm_get_slot_for_key",
        "block/keyslot-manager.c:blk_ksm_get_slot_for_key",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_get_state",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/video/fbdev/efifb.c:efifb_remove",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_hw_is_prepared",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_exit",
        "drivers/tty/serdev/core.c:devm_serdev_device_release",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_drop_link",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_read",
        "drivers/spi/spi-mem.c:spi_mem_exec_op",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975792,
      "name": "__pm_runtime_idle",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587545377,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1050",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_release_supplier"
      ],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "fs/debugfs/file.c:debugfs_show_regset32",
        "block/keyslot-manager.c:blk_ksm_evict_key",
        "block/keyslot-manager.c:blk_ksm_evict_key",
        "block/keyslot-manager.c:blk_ksm_get_slot_for_key",
        "block/keyslot-manager.c:blk_ksm_get_slot_for_key",
        "block/keyslot-manager.c:blk_ksm_get_slot_for_key",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_get_state",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_hw_is_prepared",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_exit",
        "drivers/tty/serdev/core.c:devm_serdev_device_release",
        "drivers/base/core.c:device_link_add",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/netlink.c:ethnl_ops_complete",
        "net/ethtool/netlink.c:ethnl_ops_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587540784,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588882003,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1071",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_drop_link",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_put_suppliers"
      ],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "fs/debugfs/file.c:debugfs_show_regset32",
        "block/blk-crypto-profile.c:__blk_crypto_evict_key",
        "block/blk-crypto-profile.c:__blk_crypto_evict_key",
        "block/blk-crypto-profile.c:blk_crypto_get_keyslot",
        "block/blk-crypto-profile.c:blk_crypto_get_keyslot",
        "block/blk-crypto-profile.c:blk_crypto_get_keyslot",
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_get_state",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_hw_is_prepared",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_exit",
        "drivers/tty/serdev/core.c:devm_serdev_device_release",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/netlink.c:ethnl_ops_complete",
        "net/ethtool/netlink.c:ethnl_ops_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588873456,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590390515,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1084",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_drop_link",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_put_suppliers"
      ],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "fs/debugfs/file.c:debugfs_regset32_show",
        "block/blk-crypto-profile.c:__blk_crypto_evict_key",
        "block/blk-crypto-profile.c:__blk_crypto_evict_key",
        "block/blk-crypto-profile.c:blk_crypto_get_keyslot",
        "block/blk-crypto-profile.c:blk_crypto_get_keyslot",
        "block/blk-crypto-profile.c:blk_crypto_get_keyslot",
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_get_state",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_hw_is_prepared",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_exit",
        "drivers/tty/serdev/core.c:devm_serdev_device_release",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/netlink.c:ethnl_ops_complete",
        "net/ethtool/netlink.c:ethnl_ops_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590381552,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590710179,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1084",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_drop_link",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_put_suppliers"
      ],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "fs/debugfs/file.c:debugfs_regset32_show",
        "block/blk-crypto-profile.c:__blk_crypto_evict_key",
        "block/blk-crypto-profile.c:__blk_crypto_evict_key",
        "block/blk-crypto-profile.c:blk_crypto_get_keyslot",
        "block/blk-crypto-profile.c:blk_crypto_get_keyslot",
        "block/blk-crypto-profile.c:blk_crypto_get_keyslot",
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_get_state",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_hw_is_prepared",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_exit",
        "drivers/tty/serdev/core.c:devm_serdev_device_release",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/netlink.c:ethnl_default_set_doit",
        "net/ethtool/netlink.c:ethnl_ops_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590701584,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591072035,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1085",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_drop_link",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_put_suppliers"
      ],
      "caller_func": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "fs/debugfs/file.c:debugfs_regset32_show",
        "block/blk-crypto-profile.c:__blk_crypto_evict_key",
        "block/blk-crypto-profile.c:__blk_crypto_evict_key",
        "block/blk-crypto-profile.c:blk_crypto_get_keyslot",
        "block/blk-crypto-profile.c:blk_crypto_get_keyslot",
        "block/blk-crypto-profile.c:blk_crypto_get_keyslot",
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_get_state",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_apply",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_hw_is_prepared",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_exit",
        "drivers/base/core.c:device_link_add",
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:pm_runtime_remove",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:link_peers",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/netlink.c:ethnl_default_set_doit",
        "net/ethtool/netlink.c:ethnl_ops_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591063440,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499052328,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1003",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_remove",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/phy/phy-core.c:phy_pm_runtime_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_remove",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_suspend",
        "drivers/tty/serial/8250/8250_of.c:of_serial_suspend",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe",
        "drivers/tty/serdev/core.c:serdev_device_close",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_shutdown",
        "drivers/iommu/arm-smmu.c:arm_smmu_remove_device",
        "drivers/iommu/arm-smmu.c:arm_smmu_add_device",
        "drivers/iommu/arm-smmu.c:arm_smmu_add_device",
        "drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard",
        "drivers/iommu/arm-smmu.c:arm_smmu_iotlb_sync",
        "drivers/iommu/arm-smmu.c:arm_smmu_flush_iotlb_all",
        "drivers/iommu/arm-smmu.c:arm_smmu_unmap",
        "drivers/iommu/arm-smmu.c:arm_smmu_map",
        "drivers/iommu/arm-smmu.c:arm_smmu_attach_dev",
        "drivers/iommu/arm-smmu.c:arm_smmu_domain_free",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_irq",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_flush_iotlb_all",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_unmap",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_detach_dev",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_domain_free",
        "drivers/base/core.c:__device_link_free_srcu",
        "drivers/base/core.c:device_link_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/ata/libahci.c:ahci_port_stop",
        "drivers/ata/libahci.c:ahci_port_suspend",
        "drivers/ata/libahci.c:ahci_transmit_led_message",
        "drivers/ata/libahci.c:ahci_transmit_led_message",
        "drivers/ata/libahci.c:ahci_show_em_supported",
        "drivers/ata/libahci.c:ahci_store_em_buffer",
        "drivers/ata/libahci.c:ahci_store_em_buffer",
        "drivers/ata/libahci.c:ahci_read_em_buffer",
        "drivers/ata/libahci.c:ahci_read_em_buffer",
        "drivers/ata/libahci.c:ahci_read_em_buffer",
        "drivers/ata/libahci.c:ahci_show_port_cmd",
        "drivers/ata/libahci_platform.c:ahci_platform_put_resources",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_remove",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_stop",
        "drivers/clocksource/sh_tmu.c:sh_tmu_probe",
        "drivers/clocksource/sh_tmu.c:sh_tmu_probe",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_suspend",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_resume",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499052328,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231611824,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1003",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_remove",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_remove",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/bus/ti-sysc.c:sysc_remove",
        "drivers/bus/ti-sysc.c:sysc_probe",
        "drivers/bus/ti-sysc.c:sysc_probe",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/phy/phy-core.c:phy_pm_runtime_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/gpio/gpio-omap.c:omap_gpio_free",
        "drivers/gpio/gpio-omap.c:gpio_irq_bus_sync_unlock",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_remove",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_subsys_powerdown",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_shutdown",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_suspend",
        "drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_probe",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_disable",
        "drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe",
        "drivers/clk/ti/clk-dra7-atl.c:atl_clk_disable",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_free_chan_resources",
        "drivers/tty/serial/8250/8250_of.c:of_serial_suspend",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup",
        "drivers/tty/serial/omap-serial.c:serial_omap_remove",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/tty/serdev/core.c:serdev_device_close",
        "drivers/iommu/omap-iommu.c:omap_iommu_domain_deactivate",
        "drivers/iommu/omap-iommu.c:omap_iommu_detach",
        "drivers/iommu/omap-iommu.c:flush_iotlb_all",
        "drivers/iommu/omap-iommu.c:flush_iotlb_page",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_irq",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_attach_device",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_detach_device",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_flush_iotlb_all",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_unmap",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_detach_dev",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_domain_free",
        "drivers/base/core.c:__device_link_free_srcu",
        "drivers/base/core.c:device_link_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_probe",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_probe",
        "drivers/mfd/omap-usb-tll.c:omap_tll_disable",
        "drivers/mfd/omap-usb-tll.c:omap_tll_init",
        "drivers/mfd/omap-usb-tll.c:usbtll_omap_probe",
        "drivers/mfd/omap-usb-tll.c:usbtll_omap_probe",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/ata/libahci.c:ahci_port_stop",
        "drivers/ata/libahci.c:ahci_port_suspend",
        "drivers/ata/libahci.c:ahci_transmit_led_message",
        "drivers/ata/libahci.c:ahci_transmit_led_message",
        "drivers/ata/libahci.c:ahci_show_em_supported",
        "drivers/ata/libahci.c:ahci_store_em_buffer",
        "drivers/ata/libahci.c:ahci_store_em_buffer",
        "drivers/ata/libahci.c:ahci_read_em_buffer",
        "drivers/ata/libahci.c:ahci_read_em_buffer",
        "drivers/ata/libahci.c:ahci_read_em_buffer",
        "drivers/ata/libahci.c:ahci_show_port_cmd",
        "drivers/ata/libahci_platform.c:ahci_platform_put_resources",
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_remove",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-mem.c:spi_mem_access_end",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_remove",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_tx_maxrate",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_kill_vid",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_add_vid",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_stop",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open",
        "drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_ethtool_op_complete",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/musb/musb_core.c:musb_remove",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/usb/musb/musb_core.c:vbus_show",
        "drivers/usb/musb/musb_core.c:vbus_show",
        "drivers/usb/musb/musb_core.c:vbus_show",
        "drivers/usb/musb/musb_core.c:musb_ulpi_write",
        "drivers/usb/musb/musb_core.c:musb_ulpi_read",
        "drivers/rtc/rtc-omap.c:omap_rtc_remove",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_remove",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/power/avs/smartreflex.c:omap_sr_probe",
        "drivers/power/avs/smartreflex.c:omap_sr_probe",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_stop",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_probe",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_disable",
        "drivers/clocksource/sh_tmu.c:sh_tmu_probe",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_disable",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_enable",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_prescaler",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_pwm",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_match",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_load",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop",
        "drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request",
        "drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free",
        "drivers/memory/omap-gpmc.c:gpmc_suspend",
        "drivers/memory/omap-gpmc.c:gpmc_remove",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_suspend",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_resume",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_put",
        "sound/soc/soc-dapm.c:dapm_post_sequence_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231611824,
      "name": "__pm_runtime_idle",
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292225424,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1003",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/phy/phy-core.c:phy_pm_runtime_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/tty/serial/8250/8250_of.c:of_serial_suspend",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe",
        "drivers/tty/serdev/core.c:serdev_device_close",
        "drivers/base/core.c:__device_link_free_srcu",
        "drivers/base/core.c:device_link_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292225424,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276410564,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1003",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/phy/phy-core.c:phy_pm_runtime_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown",
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe",
        "drivers/tty/serdev/core.c:serdev_device_close",
        "drivers/base/core.c:__device_link_free_srcu",
        "drivers/base/core.c:device_link_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276410564,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585997824,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1003",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/phy/phy-core.c:phy_pm_runtime_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serdev/core.c:serdev_device_close",
        "drivers/base/core.c:__device_link_free_srcu",
        "drivers/base/core.c:device_link_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585997824,
      "name": "__pm_runtime_idle",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585847040,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1003",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/phy/phy-core.c:phy_pm_runtime_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_free",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/base/core.c:__device_link_free_srcu",
        "drivers/base/core.c:device_link_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585847040,
      "name": "__pm_runtime_idle",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586187632,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1003",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/phy/phy-core.c:phy_pm_runtime_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_free",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_remove",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serdev/core.c:serdev_device_close",
        "drivers/base/core.c:__device_link_free_srcu",
        "drivers/base/core.c:device_link_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586187632,
      "name": "__pm_runtime_idle",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __pm_runtime_idle(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586299056,
      "name": "__pm_runtime_idle",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1003",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_chip_pm_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_put_sync",
        "drivers/phy/phy-core.c:phy_pm_runtime_put",
        "drivers/phy/phy-core.c:phy_pm_runtime_get_sync",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_free",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_remove",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci.c:pci_config_pm_runtime_put",
        "drivers/pci/pci-driver.c:pci_device_remove",
        "drivers/pci/pci-driver.c:local_pci_probe",
        "drivers/pci/pci-sysfs.c:reset_store",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_is_enabled",
        "drivers/tty/serdev/core.c:serdev_device_close",
        "drivers/base/core.c:__device_link_free_srcu",
        "drivers/base/core.c:device_link_add",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:__device_attach_async_helper",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance",
        "drivers/base/power/qos.c:dev_pm_qos_update_flags",
        "drivers/base/power/qos.c:dev_pm_qos_hide_flags",
        "drivers/base/power/qos.c:dev_pm_qos_expose_flags",
        "drivers/base/power/runtime.c:pm_runtime_put_suppliers",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_put_suppliers",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_host",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_target",
        "drivers/scsi/scsi_pm.c:scsi_autopm_put_device",
        "drivers/scsi/scsi_pm.c:scsi_autopm_get_device",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/driver.c:usb_autopm_get_interface",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autoresume_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/host/ohci-platform.c:ohci_platform_remove",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586299056,
      "name": "__pm_runtime_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
