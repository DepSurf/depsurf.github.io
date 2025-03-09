# Function: <code>__ioremap</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * __ioremap(phys_addr_t phys_addr, size_t size, pgprot_t prot)
```

```json
{
  "name": "__ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490344120,
      "name": "__ioremap",
      "external": true,
      "loc": "arch/arm64/mm/ioremap.c:65",
      "file": "arch/arm64/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot",
        "virt/kvm/arm/mmu.c:create_hyp_io_mappings",
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:ioremap_cache",
        "kernel/iomem.c:ioremap_cache",
        "kernel/iomem.c:ioremap_cache",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/irqchip/irq-gic.c:gic_v2_acpi_init",
        "drivers/irqchip/irq-gic.c:gic_v2_acpi_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one",
        "drivers/irqchip/irq-gic-v3.c:gic_acpi_init",
        "drivers/irqchip/irq-gic-v3.c:gic_acpi_parse_madt_gicc",
        "drivers/irqchip/irq-gic-v3.c:gic_acpi_parse_madt_redist",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init",
        "drivers/irqchip/irq-sni-exiu.c:exiu_init",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/ecam.c:pci_ecam_create",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_register",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/reset/reset-sunxi.c:sun6i_reset_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/tty/serial/msm_serial.c:msm_request_port",
        "drivers/mfd/syscon.c:of_syscon_register",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_init",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable_device",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/edac/altera_edac.c:altr_sdram_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_register",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_find_best_frame",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_get_cntfrq",
        "drivers/of/address.c:of_io_request_and_map",
        "drivers/of/address.c:of_io_request_and_map",
        "drivers/of/address.c:of_iomap",
        "drivers/of/address.c:of_iomap",
        "drivers/of/address.c:of_iomap",
        "drivers/mailbox/pl320-ipc.c:pl320_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490344120,
      "name": "__ioremap",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void * __ioremap(phys_addr_t phys_addr, size_t size, pgprot_t prot)
```
</details>
</li>
</ul>
