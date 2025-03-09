# Function: <code>bitmap_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585776336,
      "name": "bitmap_free",
      "external": false,
      "loc": "drivers/md/bitmap.c:1674",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_destroy",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_copy_from_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776336,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586174512,
      "name": "bitmap_free",
      "external": false,
      "loc": "drivers/md/bitmap.c:1702",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_copy_from_slot",
        "drivers/md/bitmap.c:bitmap_copy_from_slot",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586174512,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586378416,
      "name": "bitmap_free",
      "external": false,
      "loc": "drivers/md/bitmap.c:1730",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_copy_from_slot",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586378416,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
void bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586482384,
      "name": "bitmap_free",
      "external": true,
      "loc": "drivers/md/bitmap.c:1732",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:get_bitmap_from_slot",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586482384,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586950064,
      "name": "bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1736",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950064,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void bitmap_free(struct bitmap * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587245152,
      "name": "bitmap_free",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1736",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:get_bitmap_from_slot",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587245152,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583923984,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1136",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583923984,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584103168,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1164",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103168,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225952,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1184",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225952,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584631568,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1259",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631568,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584750608,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1259",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "lib/pldmfw/pldmfw.c:pldmfw_free_priv",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584750608,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584779438,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1270",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:devm_bitmap_alloc"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_queue_show",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778784,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585210190,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1401",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:devm_bitmap_alloc"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/watch_queue.c:__put_watch_queue",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:validate_slab_cache",
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_queue_show",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585209296,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586046578,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1431",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:devm_bitmap_alloc"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/irq/irq_sim.c:devm_irq_domain_create_sim",
        "kernel/irq/irq_sim.c:irq_domain_create_sim",
        "kernel/watch_queue.c:__put_watch_queue",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:validate_slab_cache",
        "io_uring/io_uring.c:__io_sqe_files_unregister",
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/iommu/intel/iommu.c:free_dmar_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_queue_show",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045488,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587030034,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1412",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:devm_bitmap_alloc"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/irq/irq_sim.c:devm_irq_domain_create_sim",
        "kernel/irq/irq_sim.c:irq_domain_create_sim",
        "kernel/watch_queue.c:__put_watch_queue",
        "mm/vmscan.c:lru_gen_exit_memcg",
        "mm/vmscan.c:lru_gen_exit_memcg",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:validate_slab_cache",
        "io_uring/filetable.c:io_free_file_tables",
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/iommu/intel/iommu.c:free_dmar_iommu",
        "drivers/iommu/intel/iommu.c:free_dmar_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_queue_show",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587028416,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587285193,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1412",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:devm_bitmap_alloc"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/irq/irq_sim.c:devm_irq_domain_create_sim",
        "kernel/irq/irq_sim.c:irq_domain_create_sim",
        "kernel/watch_queue.c:__put_watch_queue",
        "mm/vmscan.c:lru_gen_exit_memcg",
        "mm/vmscan.c:lru_gen_exit_memcg",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:validate_slab_cache",
        "io_uring/filetable.c:io_free_file_tables",
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_queue_show",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587283568,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587572185,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:736",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:devm_bitmap_alloc"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/irq/irq_sim.c:devm_irq_domain_create_sim",
        "kernel/irq/irq_sim.c:irq_domain_create_sim",
        "kernel/watch_queue.c:__put_watch_queue",
        "mm/vmscan.c:lru_gen_exit_memcg",
        "mm/vmscan.c:lru_gen_exit_memcg",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:slab_debug_trace_open",
        "mm/slub.c:validate_slab_cache",
        "io_uring/filetable.c:io_free_file_tables",
        "lib/pldmfw/pldmfw.c:pldmfw_flash_image",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/ptp/ptp_clock.c:ptp_clock_register",
        "drivers/ptp/ptp_clock.c:ptp_clock_release",
        "drivers/ptp/ptp_chardev.c:ptp_release",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_queue_show",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587571536,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496099784,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1184",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_free_bitmap",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496099784,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229426944,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1184",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229426944,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290345472,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1184",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290345472,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275169150,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1184",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275169150,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194688,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1184",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194688,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584129904,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1184",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irq_sim.c:irq_sim_fini",
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584129904,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584178448,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1184",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178448,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void bitmap_free(const long unsigned int * bitmap)
```

```json
{
  "name": "bitmap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584282784,
      "name": "bitmap_free",
      "external": true,
      "loc": "lib/bitmap.c:1184",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "mm/slub.c:validate_store",
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shutdown",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/probe.c:pci_release_dev",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_release",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282784,
      "name": "bitmap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bitmap * bitmap</code> ➡️ <code>const long unsigned int * bitmap</code>
</li>
</ul>
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
