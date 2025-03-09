# Function: <code>__raw_readw</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
u16 __raw_readw(volatile const void * addr)
```

```json
{
  "name": "__raw_readw",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496178392,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "lib/logic_pio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496559632,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/pinctrl/pinctrl-single.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-single.c:pcs_readw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496643064,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496759520,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_read16be",
        "drivers/gpio/gpio-mmio.c:bgpio_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496818276,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496904256,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496958196,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497035732,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497096972,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/pci/controller/pcie-cadence-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_get_msi",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497131576,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/pci/controller/pcie-altera.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-altera.c:s10_rp_read_cfg",
        "drivers/pci/controller/pcie-altera.c:s10_altera_pcie_link_up"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/pci/controller/pcie-mobiveil.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497155516,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497182848,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/pci/controller/dwc/pcie-qcom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_link_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497380040,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497666548,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:cpc_read",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan",
        "drivers/acpi/cppc_acpi.c:check_pcc_chan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497935360,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/clk/renesas/rcar-usb2-clock-sel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:usb2_clock_sel_enable_extal_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498178944,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:vm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498181296,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498189144,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498568244,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:mem16_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498609148,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498612044,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498624280,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/amba-pl011.c:pl011_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498816900,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499184788,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16be",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499791492,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_data_xfer32",
        "drivers/ata/libata-sff.c:ata_sff_data_xfer",
        "drivers/ata/libata-sff.c:ata_sff_data_xfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500097752,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_write",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_mii_out",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500873968,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:dw_readl",
        "drivers/i2c/busses/i2c-designware-common.c:dw_readl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500884948,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/i2c/busses/i2c-omap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_unprepare_recovery",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_prepare_recovery",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_set_scl",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_get_sda",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_get_scl",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_isr",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_isr",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_wait_for_bb",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_recover_bus"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg"
      ]
    },
    {
      "addr": 18446603336501526376,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501574796,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501584072,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_set_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501584816,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/clocksource/mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/mmio.c:clocksource_mmio_readw_down",
        "drivers/clocksource/mmio.c:clocksource_mmio_readw_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501671560,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:60",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:read_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500882848,
      "name": "__raw_readw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__raw_readw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224595356,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "arch/arm/mach-omap2/omap_hwmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/omap_hwmod.c:_wait_softreset_complete",
        "arch/arm/mach-omap2/omap_hwmod.c:_wait_softreset_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 3229745160,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/irqchip/irq-renesas-rza1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_set_type",
        "drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_eoi"
      ],
      "caller_func": []
    },
    {
      "addr": 3229748008,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/irqchip/irq-vf610-mscm-ir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3229773920,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/bus/ti-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229860384,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pinctrl/pinctrl-rza1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_set",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_get",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_get_direction",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3229861184,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pinctrl/pinctrl-rza2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux",
        "drivers/pinctrl/pinctrl-rza2.c:rza2_chip_get_direction",
        "drivers/pinctrl/pinctrl-rza2.c:rza2_pin_to_gpio"
      ],
      "caller_func": []
    },
    {
      "addr": 3229868992,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pinctrl/pinctrl-single.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-single.c:pcs_readw"
      ],
      "caller_func": []
    },
    {
      "addr": 3229955568,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230040048,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_read16be",
        "drivers/gpio/gpio-mmio.c:bgpio_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 3230044256,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/gpio/gpio-htc-egpio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-htc-egpio.c:egpio_write_cache",
        "drivers/gpio/gpio-htc-egpio.c:egpio_get",
        "drivers/gpio/gpio-htc-egpio.c:egpio_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3230063328,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/gpio/gpio-omap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-omap.c:omap_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230101608,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3230178988,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 3230180408,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 3230224740,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_tigerpoint_bm_sts"
      ],
      "caller_func": []
    },
    {
      "addr": 3230300184,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pci/controller/pcie-cadence-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_get_msi",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi"
      ],
      "caller_func": []
    },
    {
      "addr": 3230307500,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pci/controller/pci-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_rd_conf"
      ],
      "caller_func": []
    },
    {
      "addr": 3230338988,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pci/controller/pci-v3-semi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3230342488,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pci/controller/pcie-altera.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-altera.c:s10_rp_read_cfg",
        "drivers/pci/controller/pcie-altera.c:s10_altera_pcie_link_up"
      ],
      "caller_func": []
    },
    {
      "addr": 3230361124,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230384528,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/pci/controller/dwc/pcie-qcom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_link_up"
      ],
      "caller_func": []
    },
    {
      "addr": 3243763844,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/clk/renesas/clk-rz.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230681712,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/clk/renesas/rcar-usb2-clock-sel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230774688,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/clk/ti/adpll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230863608,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/dma/ti/omap-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230942044,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:vm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3230944852,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3230952904,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 3231204160,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:mem16_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 3231232608,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3231239560,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 3243856888,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/amba-pl011.c:pl011_console_putchar",
        "drivers/tty/serial/amba-pl011.c:pl011_set_termios",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts",
        "drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts",
        "drivers/tty/serial/amba-pl011.c:pl011_put_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_get_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_get_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_get_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_get_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_break_ctl",
        "drivers/tty/serial/amba-pl011.c:pl011_set_mctrl",
        "drivers/tty/serial/amba-pl011.c:pl011_get_mctrl",
        "drivers/tty/serial/amba-pl011.c:pl011_tx_empty",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_tx_char",
        "drivers/tty/serial/amba-pl011.c:pl011_start_tx",
        "drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty",
        "drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 3231311484,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/tty/serial/omap-serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/omap-serial.c:serial_omap_mdr1_errataset",
        "drivers/tty/serial/omap-serial.c:serial_omap_mdr1_errataset",
        "drivers/tty/serial/omap-serial.c:serial_omap_console_write",
        "drivers/tty/serial/omap-serial.c:omap_serial_early_putc",
        "drivers/tty/serial/omap-serial.c:serial_omap_poll_get_char",
        "drivers/tty/serial/omap-serial.c:serial_omap_poll_get_char",
        "drivers/tty/serial/omap-serial.c:serial_omap_pm",
        "drivers/tty/serial/omap-serial.c:serial_omap_set_termios",
        "drivers/tty/serial/omap-serial.c:serial_omap_set_termios",
        "drivers/tty/serial/omap-serial.c:serial_omap_shutdown",
        "drivers/tty/serial/omap-serial.c:serial_omap_shutdown",
        "drivers/tty/serial/omap-serial.c:serial_omap_shutdown",
        "drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl",
        "drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl",
        "drivers/tty/serial/omap-serial.c:serial_omap_tx_empty",
        "drivers/tty/serial/omap-serial.c:serial_omap_irq",
        "drivers/tty/serial/omap-serial.c:serial_omap_irq",
        "drivers/tty/serial/omap-serial.c:serial_omap_irq",
        "drivers/tty/serial/omap-serial.c:serial_omap_irq",
        "drivers/tty/serial/omap-serial.c:check_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 3231428336,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 3231718644,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16be",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le"
      ],
      "caller_func": []
    },
    {
      "addr": 3231772348,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/mfd/asic3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/asic3.c:asic3_clk_disable",
        "drivers/mfd/asic3.c:asic3_clk_enable",
        "drivers/mfd/asic3.c:asic3_gpio_set",
        "drivers/mfd/asic3.c:asic3_gpio_get",
        "drivers/mfd/asic3.c:asic3_gpio_direction",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/asic3.c:asic3_unmask_irq",
        "drivers/mfd/asic3.c:asic3_unmask_gpio_irq",
        "drivers/mfd/asic3.c:asic3_mask_irq",
        "drivers/mfd/asic3.c:asic3_mask_gpio_irq",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/asic3.c:asic3_set_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3231789784,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/mfd/tc6393xb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc6393xb.c:tc6393xb_suspend",
        "drivers/mfd/tc6393xb.c:tc6393xb_fb_disable",
        "drivers/mfd/tc6393xb.c:tc6393xb_fb_enable",
        "drivers/mfd/tc6393xb.c:tc6393xb_ohci_disable",
        "drivers/mfd/tc6393xb.c:tc6393xb_ohci_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3232235480,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232339452,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/mtd/maps/map_funcs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/maps/map_funcs.c:simple_map_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3232378864,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/mtd/nand/raw/nand_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/nand/raw/nand_legacy.c:nand_read_byte16"
      ],
      "caller_func": []
    },
    {
      "addr": 3232901400,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc",
        "drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 3233002132,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number",
        "drivers/usb/host/uhci-hcd.c:uhci_irq",
        "drivers/usb/host/uhci-hcd.c:uhci_irq",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:start_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/uhci-hcd.c:any_ports_active",
        "drivers/usb/host/uhci-hcd.c:any_ports_active",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status"
      ],
      "caller_func": []
    },
    {
      "addr": 3233176052,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/usb/musb/musb_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_core.c:musb_default_read_fifo",
        "drivers/usb/musb/musb_core.c:musb_default_readw"
      ],
      "caller_func": []
    },
    {
      "addr": 3233341308,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/rtc/rtc-s3c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-s3c.c:s3c6410_rtc_restore_tick_cnt",
        "drivers/rtc/rtc-s3c.c:s3c6410_rtc_save_tick_cnt",
        "drivers/rtc/rtc-s3c.c:s3c6410_rtc_enable_tick",
        "drivers/rtc/rtc-s3c.c:s3c2416_rtc_select_tick_clk",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c6410_rtc_disable",
        "drivers/rtc/rtc-s3c.c:s3c24xx_rtc_disable",
        "drivers/rtc/rtc-s3c.c:s3c24xx_rtc_enable",
        "drivers/rtc/rtc-s3c.c:s3c24xx_rtc_enable",
        "drivers/rtc/rtc-s3c.c:s3c24xx_rtc_enable",
        "drivers/rtc/rtc-s3c.c:s3c24xx_rtc_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3233382596,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": []
    },
    {
      "addr": 3233400676,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/i2c/busses/i2c-omap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_runtime_suspend",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_unprepare_recovery",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_prepare_recovery",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_set_scl",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_get_sda",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_get_scl",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_data",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_isr",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_isr",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_wait_for_bb",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_recover_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 3233536640,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/thermal/samsung/exynos_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3233959456,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/mmc/host/sdhci.c:__sdhci_read_caps",
        "drivers/mmc/host/sdhci.c:sdhci_irq",
        "drivers/mmc/host/sdhci.c:sdhci_irq",
        "drivers/mmc/host/sdhci.c:sdhci_irq",
        "drivers/mmc/host/sdhci.c:sdhci_irq",
        "drivers/mmc/host/sdhci.c:sdhci_execute_tuning",
        "drivers/mmc/host/sdhci.c:sdhci_reset_tuning",
        "drivers/mmc/host/sdhci.c:sdhci_start_tuning",
        "drivers/mmc/host/sdhci.c:sdhci_start_signal_voltage_switch",
        "drivers/mmc/host/sdhci.c:sdhci_start_signal_voltage_switch",
        "drivers/mmc/host/sdhci.c:sdhci_start_signal_voltage_switch",
        "drivers/mmc/host/sdhci.c:sdhci_set_ios",
        "drivers/mmc/host/sdhci.c:sdhci_set_ios",
        "drivers/mmc/host/sdhci.c:sdhci_set_ios",
        "drivers/mmc/host/sdhci.c:sdhci_set_uhs_signaling",
        "drivers/mmc/host/sdhci.c:sdhci_enable_clk",
        "drivers/mmc/host/sdhci.c:sdhci_enable_clk",
        "drivers/mmc/host/sdhci.c:sdhci_calc_clk",
        "drivers/mmc/host/sdhci.c:sdhci_get_preset_value",
        "drivers/mmc/host/sdhci.c:sdhci_get_preset_value",
        "drivers/mmc/host/sdhci.c:sdhci_get_preset_value",
        "drivers/mmc/host/sdhci.c:sdhci_get_preset_value",
        "drivers/mmc/host/sdhci.c:sdhci_get_preset_value",
        "drivers/mmc/host/sdhci.c:sdhci_get_preset_value",
        "drivers/mmc/host/sdhci.c:sdhci_send_command",
        "drivers/mmc/host/sdhci.c:sdhci_send_command",
        "drivers/mmc/host/sdhci.c:sdhci_prepare_data",
        "drivers/mmc/host/sdhci.c:sdhci_prepare_data",
        "drivers/mmc/host/sdhci.c:sdhci_do_enable_v4_mode",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs"
      ],
      "caller_func": []
    },
    {
      "addr": 3233997336,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/mmc/host/sdhci-esdhc-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le"
      ],
      "caller_func": []
    },
    {
      "addr": 3234043720,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 3234087056,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/clocksource/sh_mtu2.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234095912,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_set_next"
      ],
      "caller_func": []
    },
    {
      "addr": 3234099592,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:75",
      "file": "drivers/clocksource/mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/mmio.c:clocksource_mmio_readw_down",
        "drivers/clocksource/mmio.c:clocksource_mmio_readw_up"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__raw_readw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282948832,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/powerpc/include/asm/io.h:306",
      "file": "arch/powerpc/sysdev/xive/native.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xive/native.c:xive_native_update_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282953852,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/powerpc/include/asm/io.h:306",
      "file": "arch/powerpc/sysdev/xive/spapr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xive/spapr.c:xive_spapr_update_pending"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__raw_readw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275447032,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/pinctrl/pinctrl-single.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-single.c:pcs_readw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275501990,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_read16be",
        "drivers/gpio/gpio-mmio.c:bgpio_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275527928,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275592870,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275629928,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_tigerpoint_bm_sts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275694558,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275732506,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/pci/controller/pcie-cadence-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_get_msi",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275740200,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275958816,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:vm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275961246,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275969434,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276172480,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:mem16_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276198394,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276207432,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276314442,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read16"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276479782,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16be",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276941444,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_data_xfer32",
        "drivers/ata/libata-sff.c:ata_sff_data_xfer",
        "drivers/ata/libata-sff.c:ata_sff_data_xfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277335896,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc",
        "drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277422658,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number",
        "drivers/usb/host/uhci-hcd.c:uhci_irq",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/uhci-hcd.c:any_ports_active",
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule",
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule",
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule",
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule",
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule",
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277666324,
      "name": "__raw_readw",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:68",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:dw_readl",
        "drivers/i2c/busses/i2c-designware-common.c:dw_readl"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
u16 __raw_readw(volatile const void * addr)
```
</details>
</li>
</ul>
