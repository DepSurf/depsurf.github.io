# Function: <code>dev_driver_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584379517,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:96",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:dev_vprintk_emit",
        "drivers/base/core.c:__dev_printk"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "drivers/phy/phy-core.c:devm_phy_put",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584380560,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584715850,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:96",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/memremap.c:devm_memremap_pages_release",
        "kernel/memremap.c:devm_memremap_pages_release",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715760,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584902538,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:662",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/memremap.c:devm_memremap_pages_release",
        "kernel/memremap.c:devm_memremap_pages_release",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584902448,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584987930,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:663",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/memremap.c:devm_memremap_pages_release",
        "kernel/memremap.c:devm_memremap_pages_release",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/rtc/rtc-sysfs.c:name_show",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584987584,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585409866,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:666",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/memremap.c:devm_memremap_pages_release",
        "kernel/memremap.c:devm_memremap_pages_release",
        "mm/hmm.c:hmm_devmem_release",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/rtc/rtc-sysfs.c:name_show",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585409520,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585651890,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:699",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages_release",
        "kernel/memremap.c:devm_memremap_pages_release",
        "mm/hmm.c:hmm_devmem_release",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/rtc/rtc-sysfs.c:name_show",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585651536,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585781426,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:761",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages_release",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/dd.c:driver_deferred_probe_check_state",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/rtc/sysfs.c:name_show",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781328,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586024630,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:906",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:devm_memremap_pages_release",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-core.c:ata_host_activate",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/rtc/sysfs.c:name_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586015136,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586172220,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:943",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/rtc/sysfs.c:name_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586162432,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586918608,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:1421",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_key_revalidate",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_alloc_split_dma_aligned_buf",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/rtc/sysfs.c:name_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918608,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587005344,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:1822",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/dd.c:device_set_deferred_probe_reason",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_key_revalidate",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:adjust_dev_dax_range",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/rtc/sysfs.c:name_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005344,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586887984,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:2034",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/dd.c:device_set_deferred_probe_reason",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:adjust_dev_dax_range",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/rtc/sysfs.c:name_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586887984,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587449536,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:2071",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unbind",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/dd.c:device_set_deferred_probe_reason",
        "drivers/base/power/wakeirq.c:dev_pm_attach_wake_irq",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:adjust_dev_dax_range",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/rtc/sysfs.c:name_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449536,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588767264,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:2083",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unbind",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/dd.c:device_set_deferred_probe_reason",
        "drivers/base/power/wakeirq.c:dev_pm_attach_wake_irq",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:adjust_dev_dax_range",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/vfio/vfio.c:__vfio_register_dev",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/rtc/sysfs.c:name_show",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588767264,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590258544,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:2320",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/doe.c:pcim_doe_create_mb",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unbind",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/dd.c:device_set_deferred_probe_reason",
        "drivers/base/power/wakeirq.c:dev_pm_attach_wake_irq",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:adjust_dev_dax_range",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/rtc/sysfs.c:name_show",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590258544,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590577808,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:2326",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unbind",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/dd.c:device_set_deferred_probe_reason",
        "drivers/base/power/wakeirq.c:dev_pm_attach_wake_irq",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:adjust_dev_dax_range",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/rtc/sysfs.c:name_show",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590577808,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590936208,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:2341",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_direct_map_page",
        "kernel/dma/direct.c:dma_direct_map_page",
        "kernel/dma/swiotlb.c:swiotlb_map",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/dma/swiotlb.c:swiotlb_bounce",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/phy/phy-core.c:phy_get",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci-driver.c:pci_pm_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_unbind",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/dd.c:device_set_deferred_probe_reason",
        "drivers/base/power/wakeirq.c:dev_pm_attach_wake_irq",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_resize",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:adjust_dev_dax_range",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:devm_register_dax_mapping",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/gpu/drm/drm_aperture.c:devm_aperture_acquire_from_firmware",
        "drivers/gpu/drm/drm_connector.c:drmm_connector_init",
        "drivers/gpu/drm/drm_crtc.c:__drmm_crtc_init_with_planes",
        "drivers/gpu/drm/drm_edid.c:drm_edid_read_switcheroo",
        "drivers/gpu/drm/drm_edid.c:drm_get_edid_switcheroo",
        "drivers/gpu/drm/drm_edid.c:drm_edid_read_custom",
        "drivers/gpu/drm/drm_encoder.c:__drmm_encoder_init",
        "drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_remove",
        "drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_free",
        "drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb",
        "drivers/gpu/drm/drm_plane.c:drm_plane_register_all",
        "drivers/gpu/drm/drm_plane.c:__drm_universal_plane_alloc",
        "drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init",
        "drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init",
        "drivers/gpu/drm/drm_vblank.c:drm_handle_vblank",
        "drivers/gpu/drm/drm_vblank.c:drm_handle_vblank",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_restore",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_restore",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_on",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_on",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_set_max_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_set_max_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_reset",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_reset",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_off",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_one_vblank",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_one_vblank",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_one_vblank",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_put",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_put",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_get",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_enable",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_count_and_time",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal",
        "drivers/gpu/drm/drm_vblank.c:drm_calc_timestamping_constants",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_init_release",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_disable_and_save",
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_accurate_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:drm_update_vblank_count",
        "drivers/gpu/drm/drm_vblank.c:__get_vblank_counter",
        "drivers/gpu/drm/drm_vblank.c:__get_vblank_counter",
        "drivers/gpu/drm/drm_vblank_work.c:drm_vblank_cancel_pending_works",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_get_sg_table",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vm_open",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vm_open",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_fault",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_purge",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vunmap",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vmap",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_unpin",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_pin",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_put_pages",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_free",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_free",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_object_get_sg_table",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_object_pin",
        "drivers/gpu/drm/drm_format_helper.c:drm_fb_xrgb8888_to_mono",
        "drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_get_obj",
        "drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_get_obj",
        "drivers/gpu/drm/drm_plane_helper.c:drm_plane_helper_disable_primary",
        "drivers/gpu/drm/drm_plane_helper.c:drm_plane_helper_update_primary",
        "drivers/gpu/drm/drm_probe_helper.c:check_connector_changed",
        "drivers/gpu/drm/drm_probe_helper.c:check_connector_changed",
        "drivers/gpu/drm/drm_probe_helper.c:__drm_helper_update_and_validate",
        "drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_setup",
        "drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_setup",
        "drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_helper_fb_dirty",
        "drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_helper_fb_dirty",
        "drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_damage_work",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci.c:xhci_map_temp_buffer",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/rtc/sysfs.c:name_show",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590936208,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498968928,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:943",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "arch/arm64/mm/dma-mapping.c:arch_setup_dma_ops",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/soc/fsl/qbman/qman.c:qman_init_fq",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/ata/libahci.c:ahci_port_start",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/rtc/sysfs.c:name_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/firmware/qcom_scm-64.c:qcom_scm_call",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498957968,
      "name": "dev_driver_string",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231538620,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:943",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_handle_iobase_change",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages",
        "drivers/iommu/omap-iommu.c:omap_iommu_attach_dev",
        "drivers/iommu/omap-iommu.c:iopte_alloc",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_map",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/ata/libahci.c:ahci_port_start",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/usb/musb/musb_host.c:musb_h_tx_flush_fifo",
        "drivers/rtc/sysfs.c:name_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer",
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/firmware/qcom_scm-32.c:qcom_scm_call",
        "sound/core/init.c:snd_card_new",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231531460,
      "name": "dev_driver_string",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292115904,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:943",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe",
        "drivers/char/tpm/tpm_ibmvtpm.c:ibmvtpm_interrupt",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-core.c:ata_host_activate",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/rtc/sysfs.c:name_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292101840,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276348642,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:943",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/rtc/sysfs.c:name_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276339944,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585932588,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:943",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/rtc/sysfs.c:name_show",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585922800,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585781724,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:943",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/acpi/nfit/core.c:acpi_nfit_scrub",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/btt.c:btt_meta_init",
        "drivers/nvdimm/btt.c:btt_meta_init",
        "drivers/nvdimm/btt.c:btt_meta_init",
        "drivers/nvdimm/btt.c:btt_meta_init",
        "drivers/nvdimm/btt.c:btt_meta_init",
        "drivers/nvdimm/btt.c:btt_meta_init",
        "drivers/nvdimm/blk.c:to_dev_offset",
        "drivers/nvdimm/blk.c:to_dev_offset",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/rtc/sysfs.c:name_show",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771936,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586122236,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:943",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/rtc/sysfs.c:name_show",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586112448,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
const char * dev_driver_string(const struct device * dev)
```

```json
{
  "name": "dev_driver_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586230844,
      "name": "dev_driver_string",
      "external": true,
      "loc": "drivers/base/core.c:943",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:__dev_printk",
        "drivers/base/core.c:dev_vprintk_emit",
        "drivers/base/core.c:dev_vprintk_emit"
      ],
      "caller_func": [
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_end",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "kernel/trace/power-traces.c:trace_event_raw_event_device_pm_callback_start",
        "lib/dynamic_debug.c:__dynamic_ibdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_dev_dbg",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/iommu/iommu-traces.c:trace_event_raw_event_iommu_error",
        "drivers/base/power/trace.c:show_trace_dev_match",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:__nvdimm_create",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_label_update",
        "drivers/nvdimm/namespace_devs.c:pmem_sector_size",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:devm_nsio_disable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/dax/bus.c:alloc_dax_region",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_sff_activate_host",
        "drivers/ata/libata-sff.c:ata_pci_sff_init_host",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_iommu_group_notifier",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/rtc/sysfs.c:name_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586223920,
      "name": "dev_driver_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
