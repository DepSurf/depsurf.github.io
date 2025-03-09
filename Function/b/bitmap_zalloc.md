# Function: <code>bitmap_zalloc</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583924128,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1130",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583924128,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584103184,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1158",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103184,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225968,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1178",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225968,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584632144,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1253",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632144,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584751184,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1253",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751184,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780080,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1264",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_queue_show",
        "net/core/net-sysfs.c:xps_queue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780080,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585210432,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1395",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_queue_show",
        "net/core/net-sysfs.c:xps_queue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210432,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586046944,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1412",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irq_sim.c:irq_domain_create_sim",
        "io_uring/io_uring.c:io_sqe_files_register",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/iommu/intel/iommu.c:iommu_init_domains",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_queue_show",
        "net/core/net-sysfs.c:xps_queue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046944,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587030736,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1393",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irq_sim.c:irq_domain_create_sim",
        "mm/vmscan.c:iterate_mm_list",
        "io_uring/filetable.c:io_alloc_file_tables",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:iommu_init_domains",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_queue_show",
        "net/core/net-sysfs.c:xps_queue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030736,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587285888,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1393",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irq_sim.c:irq_domain_create_sim",
        "io_uring/filetable.c:io_alloc_file_tables",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:iommu_init_domains",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-zone.c:dm_zone_revalidate_cb",
        "drivers/md/dm-zone.c:dm_zone_revalidate_cb",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_queue_show",
        "net/core/net-sysfs.c:xps_queue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587285888,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587572880,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:717",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irq_sim.c:irq_domain_create_sim",
        "io_uring/filetable.c:io_alloc_file_tables",
        "lib/pldmfw/pldmfw.c:pldm_parse_one_record",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:iommu_init_domains",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-zone.c:dm_zone_revalidate_cb",
        "drivers/md/dm-zone.c:dm_zone_revalidate_cb",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_queue_show",
        "net/core/net-sysfs.c:xps_queue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587572880,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496099840,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1178",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496099840,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229426964,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1178",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229426964,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290345520,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1178",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290345520,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275169174,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1178",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275169174,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194704,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1178",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194704,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584129920,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1178",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irq_sim.c:irq_sim_init",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584129920,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584178464,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1178",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178464,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```

```json
{
  "name": "bitmap_zalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584282800,
      "name": "bitmap_zalloc",
      "external": true,
      "loc": "lib/bitmap.c:1178",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282800,
      "name": "bitmap_zalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
long unsigned int * bitmap_zalloc(unsigned int nbits, gfp_t flags)
```
</details>
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
