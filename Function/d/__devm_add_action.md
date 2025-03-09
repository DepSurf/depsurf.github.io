# Function: <code>__devm_add_action</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __devm_add_action(struct device * dev, void (*)(void *) action, void * data, const char * name)
```

```json
{
  "name": "__devm_add_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590640544,
      "name": "__devm_add_action",
      "external": true,
      "loc": "drivers/base/devres.c:734",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/reboot.c:devm_register_restart_handler",
        "kernel/reboot.c:devm_register_power_off_handler",
        "kernel/irq/irq_sim.c:devm_irq_domain_create_sim",
        "mm/memremap.c:devm_memremap_pages",
        "lib/bitmap.c:devm_bitmap_alloc",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/probe.c:devm_pci_alloc_host_bridge",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/video/aperture.c:devm_aperture_acquire_for_platform_device",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/regulator/devres.c:devm_regulator_irq_helper",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:_devm_regulator_get_enable",
        "drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc",
        "drivers/base/power/runtime.c:devm_pm_runtime_enable",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/namespace_devs.c:init_active_labels",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/opp/core.c:devm_pm_opp_set_config",
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590640544,
      "name": "__devm_add_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int __devm_add_action(struct device * dev, void (*)(void *) action, void * data, const char * name)
```

```json
{
  "name": "__devm_add_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591000608,
      "name": "__devm_add_action",
      "external": true,
      "loc": "drivers/base/devres.c:734",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/reboot.c:devm_register_restart_handler",
        "kernel/reboot.c:devm_register_power_off_handler",
        "kernel/irq/irq_sim.c:devm_irq_domain_create_sim",
        "mm/memremap.c:devm_memremap_pages",
        "lib/bitmap.c:devm_bitmap_alloc",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/probe.c:devm_pci_alloc_host_bridge",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/video/aperture.c:devm_aperture_acquire_for_platform_device",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/regulator/devres.c:devm_regulator_irq_helper",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:_devm_regulator_get_enable",
        "drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc",
        "drivers/base/power/runtime.c:devm_pm_runtime_enable",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/namespace_devs.c:init_active_labels",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/gpu/drm/drm_bridge.c:devm_drm_bridge_add",
        "drivers/gpu/drm/drm_drv.c:__devm_drm_dev_alloc",
        "drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/opp/core.c:devm_pm_opp_set_config",
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591000608,
      "name": "__devm_add_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int __devm_add_action(struct device * dev, void (*)(void *) action, void * data, const char * name)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
