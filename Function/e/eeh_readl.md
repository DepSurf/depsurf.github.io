# Function: <code>eeh_readl</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 eeh_readl(volatile const void * addr)
```

```json
{
  "name": "eeh_readl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282591584,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "arch/powerpc/kernel/legacy_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284112272,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_gc_init_mask_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288853712,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_print_regs32"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290443840,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "lib/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290685492,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/irqchip/irq-al-fic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_handler",
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290748900,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/pinctrl/pinctrl-amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290763992,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/pinctrl/pinctrl-single.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-single.c:pcs_readl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290851112,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290856324,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290890948,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32",
        "drivers/pci/access.c:pci_generic_config_read32",
        "drivers/pci/access.c:pci_generic_config_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290992960,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290996748,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291069276,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291098052,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:msi_set_mask_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291135656,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/pci/controller/pcie-cadence-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291142052,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/pci/controller/pcie-cadence-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291147052,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/pci/controller/pci-ftpci100.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291150468,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/pci/controller/pcie-xilinx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_map_bus"
      ],
      "caller_func": [
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe"
      ]
    },
    {
      "addr": 13835058055291351188,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/video/fbdev/gxt4500.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/gxt4500.c:gxt4500_blank",
        "drivers/video/fbdev/gxt4500.c:gxt4500_blank",
        "drivers/video/fbdev/gxt4500.c:gxt4500_set_par",
        "drivers/video/fbdev/gxt4500.c:gxt4500_set_par",
        "drivers/video/fbdev/gxt4500.c:gxt4500_set_par"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291413060,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_mmio.c:vm_interrupt",
        "drivers/virtio/virtio_mmio.c:vm_get_status",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_mmio.c:vm_get_features",
        "drivers/virtio/virtio_mmio.c:vm_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291786764,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:mem32_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291818068,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/tty/serial/8250/8250_dwlib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291832636,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291840328,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291957140,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_remove_memory",
        "drivers/char/agp/generic.c:agp_generic_insert_memory",
        "drivers/char/agp/generic.c:agp_generic_insert_memory",
        "drivers/char/agp/generic.c:agp_generic_insert_memory",
        "drivers/char/agp/generic.c:agp_generic_create_gatt_table"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292391264,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293675732,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel",
        "drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear",
        "drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set",
        "drivers/usb/dwc2/core.c:dwc2_hw_is_device",
        "drivers/usb/dwc2/core.c:dwc2_hw_is_host",
        "drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts",
        "drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts",
        "drivers/usb/dwc2/core.c:dwc2_is_controller_alive",
        "drivers/usb/dwc2/core.c:dwc2_enable_acg",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293684724,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293690164,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293697288,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293752504,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_set_even_odd_frame",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_halt",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_halt",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_halt",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_halt",
        "drivers/usb/dwc2/hcd.c:dwc2_read_packet",
        "drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval",
        "drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts",
        "drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change"
      ]
    },
    {
      "addr": 13835058055293770172,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr"
      ]
    },
    {
      "addr": 13835058055293779160,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293786624,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293802016,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293846972,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_get_frame",
        "drivers/usb/host/ehci-hcd.c:ehci_get_frame",
        "drivers/usb/host/ehci-hcd.c:ehci_get_frame",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_silence_controller",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:iso_stream_schedule",
        "drivers/usb/host/ehci-hcd.c:iso_stream_schedule",
        "drivers/usb/host/ehci-hcd.c:iso_stream_schedule",
        "drivers/usb/host/ehci-hcd.c:ehci_port_power",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_status_data",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_status_data",
        "drivers/usb/host/ehci-hcd.c:set_owner",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_disable_PSE",
        "drivers/usb/host/ehci-hcd.c:ehci_disable_ASE",
        "drivers/usb/host/ehci-hcd.c:ehci_set_command_bit",
        "drivers/usb/host/ehci-hcd.c:ehci_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ehci-hcd.c:ehci_handshake",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293878960,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    },
    {
      "addr": 13835058055293917140,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:_ohci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_usb_reset",
        "drivers/usb/host/ohci-hcd.c:start_ed_unlink",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ]
    },
    {
      "addr": 13835058055293950432,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_show_status"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293989816,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_quiesce",
        "drivers/usb/host/xhci.c:xhci_quiesce",
        "drivers/usb/host/xhci.c:xhci_handshake",
        "drivers/usb/host/xhci.c:xhci_handshake"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ]
    },
    {
      "addr": 13835058055294036260,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294039528,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294063488,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294095388,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_test_and_clear_bit",
        "drivers/usb/host/xhci-hub.c:xhci_set_link_state",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ]
    },
    {
      "addr": 13835058055294123404,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294140772,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294145340,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294335504,
      "name": "eeh_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/eeh.h:399",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:dw_readl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291149472,
      "name": "eeh_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 13835058055293700016,
      "name": "eeh_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 13835058055293754240,
      "name": "eeh_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 13835058055293796752,
      "name": "eeh_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 13835058055293878960,
      "name": "eeh_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 13835058055293881888,
      "name": "eeh_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 13835058055293965184,
      "name": "eeh_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 13835058055294079008,
      "name": "eeh_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
u32 eeh_readl(volatile const void * addr)
```
</details>
</li>
</ul>
