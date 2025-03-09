# Function: <code>usleep_range_state</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void usleep_range_state(long unsigned int min, long unsigned int max, unsigned int state)
```

```json
{
  "name": "usleep_range_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592829104,
      "name": "usleep_range_state",
      "external": true,
      "loc": "kernel/time/timer.c:2068",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_try_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592829104,
      "name": "usleep_range_state",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void usleep_range_state(long unsigned int min, long unsigned int max, unsigned int state)
```

```json
{
  "name": "usleep_range_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594737824,
      "name": "usleep_range_state",
      "external": true,
      "loc": "kernel/time/timer.c:2123",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/regulator/core.c:_regulator_delay_helper",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_try_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/platform/chrome/cros_ec_proto.c:send_command",
        "net/core/dev.c:napi_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594737824,
      "name": "usleep_range_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void usleep_range_state(long unsigned int min, long unsigned int max, unsigned int state)
```

```json
{
  "name": "usleep_range_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596489856,
      "name": "usleep_range_state",
      "external": true,
      "loc": "kernel/time/timer.c:2354",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_set_low_power_state",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/regulator/core.c:_regulator_delay_helper",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_try_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command",
        "net/core/dev.c:napi_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596489856,
      "name": "usleep_range_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void usleep_range_state(long unsigned int min, long unsigned int max, unsigned int state)
```

```json
{
  "name": "usleep_range_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597031168,
      "name": "usleep_range_state",
      "external": true,
      "loc": "kernel/time/timer.c:2354",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "kernel/cpu.c:cpuhp_wait_for_sync_state",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_set_low_power_state",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/regulator/core.c:_regulator_delay_helper",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_try_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command",
        "net/core/dev.c:napi_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597031168,
      "name": "usleep_range_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void usleep_range_state(long unsigned int min, long unsigned int max, unsigned int state)
```

```json
{
  "name": "usleep_range_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597960560,
      "name": "usleep_range_state",
      "external": true,
      "loc": "kernel/time/timer.c:2370",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "kernel/cpu.c:cpuhp_wait_for_sync_state",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_set_low_power_state",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/regulator/core.c:_regulator_delay_helper",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_try_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_up",
        "drivers/mmc/core/core.c:mmc_power_up",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_select_voltage",
        "drivers/mmc/core/core.c:mmc_select_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command",
        "net/core/dev.c:napi_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597960560,
      "name": "usleep_range_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void usleep_range_state(long unsigned int min, long unsigned int max, unsigned int state)
```
</details>
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
