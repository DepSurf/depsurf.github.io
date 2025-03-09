# Function: <code>usleep_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587377904,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:1713",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/core.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587377904,
      "name": "usleep_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587880304,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:1920",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/access.c:pci_vpd_wait",
        "drivers/pci/host/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587880304,
      "name": "usleep_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588097024,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:1915",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/access.c:pci_vpd_wait",
        "drivers/pci/host/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588097024,
      "name": "usleep_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588322832,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:1905",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/access.c:pci_vpd_wait",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu_unroll",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait",
        "drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588322832,
      "name": "usleep_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588888912,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:1976",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/access.c:pci_vpd_wait",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat",
        "drivers/char/tpm/tpm-interface.c:tpm_do_selftest",
        "drivers/char/tpm/tpm-interface.c:tpm_do_selftest",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait",
        "drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588888912,
      "name": "usleep_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589267152,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:1987",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_do_selftest",
        "drivers/char/tpm/tpm-interface.c:tpm_do_selftest",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589267152,
      "name": "usleep_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589509712,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:1986",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589509712,
      "name": "usleep_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589969024,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:1990",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/core.c:dwc2_wait_for_mode",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589969024,
      "name": "usleep_range",
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590196688,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:2079",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/core.c:dwc2_wait_for_mode",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590196688,
      "name": "usleep_range",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591212768,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:2100",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pwm/pwm-lpss.c:pwm_lpss_wait_for_update",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_try_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_disable_reset",
        "drivers/mfd/arizona-core.c:arizona_disable_reset",
        "drivers/mfd/arizona-core.c:arizona_poll_reg",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_down_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/net/phy/phy_device.c:phy_poll_reset",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/net/phy/bcm84881.c:bcm84881_wait_init",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/core.c:dwc2_wait_for_mode",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:mmc_sleep",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
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
      "addr": 18446744071591212768,
      "name": "usleep_range",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591708032,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:2063",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set",
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
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_disable_reset",
        "drivers/mfd/arizona-core.c:arizona_disable_reset",
        "drivers/mfd/arizona-core.c:arizona_poll_reg",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_down_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/net/phy/phy_device.c:phy_poll_reset",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/net/phy/bcm84881.c:bcm84881_wait_init",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/core.c:dwc2_wait_for_mode",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
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
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:mmc_sleep",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
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
      "addr": 18446744071591708032,
      "name": "usleep_range",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591655408,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:2081",
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
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_disable_reset",
        "drivers/mfd/arizona-core.c:arizona_disable_reset",
        "drivers/mfd/arizona-core.c:arizona_poll_reg",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/core.c:dwc2_wait_for_mode",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
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
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
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
      "addr": 18446744071591655408,
      "name": "usleep_range",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "usleep_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579539034,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580092577,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585752696,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585837000,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585988102,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586591645,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:check_pcc_chan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586627707,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/acpi/pmic/intel_pmic_xpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586869809,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_enable_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587251186,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_try_transmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587255359,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587280152,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587282739,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587642940,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587721952,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:atmel_securam_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587755970,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588094670,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588253689,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588281093,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/spi/spi-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304668,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588317476,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588318725,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_device.c:mdio_device_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588327260,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588526837,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588560348,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:hcd_bus_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588643070,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588660703,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588702780,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588789862,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588881096,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588956193,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589155938,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589160698,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589180960,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/power/reset/mt6323-poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589574937,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589585667,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589600089,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589611592,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/sd_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589621191,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589689107,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/platform/x86/intel_scu_ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589694204,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "usleep_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579627340,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580229798,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586936088,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587028998,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587204054,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587853041,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:check_pcc_chan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587893012,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/acpi/pmic/intel_pmic_xpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588157329,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_delay_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588560245,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_try_transmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588564671,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588591976,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588594947,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588986899,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589066044,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:atmel_securam_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589100974,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589472685,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589635238,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589662929,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/spi/spi-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589691434,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_loopback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589706882,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589708675,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_device.c:mdio_device_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589717082,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589935053,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589970474,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:hcd_bus_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590059870,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590078023,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590120424,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590200668,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590309205,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590388245,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590608522,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590613506,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590617899,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/i2c/busses/i2c-designware-amdpsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590637703,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/power/reset/mt6323-poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591069857,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591081420,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591096920,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591109480,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/sd_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591119815,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591195109,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/platform/x86/intel_scu_ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591200859,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591481804,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "usleep_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579741062,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580421811,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588092891,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588147030,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_set_low_power_state",
        "drivers/pci/pci.c:pci_power_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588207074,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588434301,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589195836,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:check_pcc_chan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242116,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/acpi/pmic/intel_pmic_xpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589554545,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_delay_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589624346,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/reset/reset-simple.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590013338,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_try_transmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590018655,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590048993,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590053555,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590508003,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590595804,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:atmel_securam_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590637111,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591051645,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591236118,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591273169,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/spi/spi-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591304646,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_loopback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591323399,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591325203,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_device.c:mdio_device_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591334296,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591516685,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591563628,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:hcd_bus_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591667098,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591686167,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591733160,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591817647,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591935367,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592022587,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592165519,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592269002,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592274874,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592279403,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/i2c/busses/i2c-designware-amdpsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592301671,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/power/reset/mt6323-poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592784161,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592798484,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592815670,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592830504,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/sd_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592841895,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592934613,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/platform/x86/intel_scu_ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592941969,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593250269,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:65",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "usleep_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579787542,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580491171,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588367307,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588422582,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_set_low_power_state",
        "drivers/pci/pci.c:pci_power_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588482786,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588712141,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589489996,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:check_pcc_chan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589538852,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/acpi/pmic/intel_pmic_xpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589856321,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_delay_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589927866,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/reset/reset-simple.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590322661,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_try_transmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590327951,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590359990,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590364419,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590832099,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590937020,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:atmel_securam_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590977939,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591405693,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591595654,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591627969,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/spi/spi-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591663290,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_loopback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591681935,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591686515,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_device.c:mdio_device_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591695814,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591938077,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591985388,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:hcd_bus_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592089930,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592109492,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592156609,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592240872,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592357878,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592442184,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592589023,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592694330,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592701009,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592726775,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/power/reset/mt6323-poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619896691,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/md/dm-init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_init_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592967075,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593220561,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593234990,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593252326,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593267096,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/mmc/core/sd_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593278551,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593384338,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/platform/x86/intel_scu_ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593391729,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593711117,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "usleep_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579821321,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551059,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588662075,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/pwm/pwm-lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588718870,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_pm_reset",
        "drivers/pci/pci.c:pci_set_low_power_state",
        "drivers/pci/pci.c:pci_power_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588780306,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589013501,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589022533,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589797212,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:check_pcc_chan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589847188,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/acpi/pmic/intel_pmic_xpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590193633,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_delay_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590266186,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/reset/reset-simple.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590664053,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_try_transmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590669343,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590701638,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590705939,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591175139,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591280748,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:atmel_securam_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591321907,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual",
        "drivers/mfd/twl6040.c:twl6040_power_up_manual"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591756573,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592326614,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_delay_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592360785,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/spi/spi-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592405578,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_loopback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592424597,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592429362,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_device.c:mdio_device_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592438870,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592678509,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592725308,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:hcd_bus_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592830362,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592849924,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592897233,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592981962,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593099592,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593185912,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593333807,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593440202,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593445905,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593474631,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/power/reset/mt6323-poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622206566,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/md/dm-init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_init_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593717203,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593975329,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/mmc/core/core.c:__mmc_start_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593990014,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594007574,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594023128,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/mmc/core/sd_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594034487,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594129455,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/platform/x86/intel_scu_ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594136993,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594490125,
      "name": "usleep_range",
      "external": false,
      "loc": "include/linux/delay.h:66",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503943800,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:2079",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/psci.c:cpu_psci_cpu_kill",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/bus/fsl-mc/mc-sys.c:mc_send_command",
        "drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val",
        "drivers/phy/phy-xgene.c:xgene_phy_force_lat_summer_cal",
        "drivers/phy/phy-xgene.c:xgene_phy_force_lat_summer_cal",
        "drivers/phy/phy-xgene.c:xgene_phy_force_lat_summer_cal",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_host_init",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on",
        "drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection",
        "drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/reset/reset-qcom-aoss.c:qcom_aoss_control_reset",
        "drivers/reset/reset-qcom-aoss.c:qcom_aoss_control_assert",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_disable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_disable_stall",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable_stall",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_update_config",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:imx_phy_crbit_assert",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:iproc_mdio_wait_for_idle",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_wait_for_mode",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_setalarm",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503943800,
      "name": "usleep_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236552300,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:2079",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-meson/platsmp.c:meson8_smp_cpu_kill",
        "arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary",
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/bus/ti-sysc.c:sysc_init_module",
        "drivers/bus/ti-sysc.c:sysc_init_module",
        "drivers/bus/ti-sysc.c:sysc_init_module",
        "drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt",
        "drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_on",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_on",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_exit",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_exit",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_init",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_init",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_reset",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_wait_lock",
        "drivers/clk/ti/adpll.c:ti_adpll_prepare",
        "drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection",
        "drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id",
        "drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set",
        "drivers/soc/tegra/pmc.c:tegra_genpd_power_off",
        "drivers/soc/tegra/pmc.c:tegra_genpd_power_off",
        "drivers/soc/tegra/pmc.c:tegra_genpd_power_off",
        "drivers/soc/tegra/pmc.c:tegra_genpd_power_off",
        "drivers/soc/tegra/pmc.c:tegra_genpd_power_off",
        "drivers/soc/tegra/pmc.c:tegra_powergate_set",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/reset/reset-qcom-aoss.c:qcom_aoss_control_deassert",
        "drivers/reset/reset-qcom-aoss.c:qcom_aoss_control_assert",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_disable",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/asic3.c:asic3_leds_suspend",
        "drivers/mfd/asic3.c:asic3_mmc_enable",
        "drivers/mfd/asic3.c:asic3_mmc_enable",
        "drivers/mfd/asic3.c:ds1wm_enable",
        "drivers/mfd/asic3.c:ds1wm_enable",
        "drivers/mfd/asic3.c:ds1wm_enable",
        "drivers/mfd/asic3.c:ds1wm_enable",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_update_config",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_disable_reset",
        "drivers/mfd/arizona-core.c:arizona_disable_reset",
        "drivers/mfd/arizona-core.c:arizona_poll_reg",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx_phy_crbit_assert",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/cpsw_sl.c:cpsw_sl_wait_for_idle",
        "drivers/net/ethernet/ti/cpsw_sl.c:cpsw_sl_reset",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_wait_for_mode",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_start",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start",
        "drivers/thermal/armada_thermal.c:armada_wait_sensor_validity",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd",
        "drivers/mmc/host/sdhci.c:sdhci_start_signal_voltage_switch",
        "drivers/platform/chrome/cros_ec_proto.c:send_command",
        "drivers/memory/tegra/mc.c:tegra_mc_hotreset_assert",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236552300,
      "name": "usleep_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297796128,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:2079",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_send",
        "drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_recv",
        "drivers/char/tpm/tpm_i2c_infineon.c:wait_for_stat",
        "drivers/char/tpm/tpm_i2c_infineon.c:get_burstcount",
        "drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_write_generic",
        "drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_write_generic",
        "drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_write_generic",
        "drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read",
        "drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read",
        "drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read",
        "drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read",
        "drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read",
        "drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read",
        "drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_get_burstcount",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_write_status",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_update_config",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_disable_reset",
        "drivers/mfd/arizona-core.c:arizona_disable_reset",
        "drivers/mfd/arizona-core.c:arizona_poll_reg",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/core.c:dwc2_wait_for_mode",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297796128,
      "name": "usleep_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279807494,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:2079",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_update_config",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_disable_reset",
        "drivers/mfd/arizona-core.c:arizona_disable_reset",
        "drivers/mfd/arizona-core.c:arizona_poll_reg",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/core.c:dwc2_wait_for_mode",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279807494,
      "name": "usleep_range",
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589798976,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:2079",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/core.c:dwc2_wait_for_mode",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589798976,
      "name": "usleep_range",
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589521424,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:2079",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589521424,
      "name": "usleep_range",
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590242384,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:2079",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/core.c:dwc2_wait_for_mode",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590242384,
      "name": "usleep_range",
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
void usleep_range(long unsigned int min, long unsigned int max)
```

```json
{
  "name": "usleep_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590292688,
      "name": "usleep_range",
      "external": true,
      "loc": "kernel/time/timer.c:2079",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "drivers/pci/vpd.c:pci_vpd_wait",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:get_burstcount",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/misc/sram.c:atmel_securam_wait",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/libata-core.c:ata_msleep",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/dwc2/core.c:dwc2_wait_for_mode",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590292688,
      "name": "usleep_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max)
```
</details>
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
