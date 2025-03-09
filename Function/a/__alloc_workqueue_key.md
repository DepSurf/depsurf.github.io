# Function: <code>__alloc_workqueue_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct workqueue_struct * __alloc_workqueue_key(const char * fmt, unsigned int flags, int max_active, struct lock_class_key * key, const char * lock_name, void (anon))
```

```json
{
  "name": "__alloc_workqueue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489728,
      "name": "__alloc_workqueue_key",
      "external": true,
      "loc": "kernel/workqueue.c:3797",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/cpuset.c:cpuset_init_smp",
        "kernel/events/core.c:perf_workqueue_init",
        "mm/vmstat.c:setup_vmstat",
        "mm/backing-dev.c:default_bdi_init",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/crypto.c:ext4_init_crypto",
        "crypto/crypto_wq.c:crypto_wq_init",
        "block/bio.c:__bioset_create",
        "block/blk-core.c:blk_dev_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/block/virtio_blk.c:init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/charger-manager.c:charger_manager_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/mmc/core/core.c:mmc_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489728,
      "name": "__alloc_workqueue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1240
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
struct workqueue_struct * __alloc_workqueue_key(const char * fmt, unsigned int flags, int max_active, struct lock_class_key * key, const char * lock_name, void (anon))
```

```json
{
  "name": "__alloc_workqueue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503632,
      "name": "__alloc_workqueue_key",
      "external": true,
      "loc": "kernel/workqueue.c:3895",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/cpuset.c:cpuset_init_smp",
        "mm/swap.c:lru_init",
        "mm/vmstat.c:setup_vmstat",
        "mm/backing-dev.c:default_bdi_init",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/ext4/super.c:ext4_fill_super",
        "crypto/crypto_wq.c:crypto_wq_init",
        "block/bio.c:__bioset_create",
        "block/blk-core.c:blk_dev_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/block/virtio_blk.c:init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/charger-manager.c:charger_manager_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "net/core/net_namespace.c:net_ns_init",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503632,
      "name": "__alloc_workqueue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1253
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
struct workqueue_struct * __alloc_workqueue_key(const char * fmt, unsigned int flags, int max_active, struct lock_class_key * key, const char * lock_name, void (anon))
```

```json
{
  "name": "__alloc_workqueue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524320,
      "name": "__alloc_workqueue_key",
      "external": true,
      "loc": "kernel/workqueue.c:3923",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/cpuset.c:cpuset_init_smp",
        "mm/swap.c:lru_init",
        "mm/vmstat.c:setup_vmstat",
        "mm/backing-dev.c:default_bdi_init",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/ext4/super.c:ext4_fill_super",
        "crypto/crypto_wq.c:crypto_wq_init",
        "block/bio.c:__bioset_create",
        "block/blk-core.c:blk_dev_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "net/core/net_namespace.c:net_ns_init",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524320,
      "name": "__alloc_workqueue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1247
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
struct workqueue_struct * __alloc_workqueue_key(const char * fmt, unsigned int flags, int max_active, struct lock_class_key * key, const char * lock_name, void (anon))
```

```json
{
  "name": "__alloc_workqueue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512128,
      "name": "__alloc_workqueue_key",
      "external": true,
      "loc": "kernel/workqueue.c:3932",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:default_bdi_init",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/ext4/super.c:ext4_fill_super",
        "crypto/crypto_wq.c:crypto_wq_init",
        "block/bio.c:bioset_create",
        "block/blk-core.c:blk_dev_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "net/core/net_namespace.c:net_ns_init",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512128,
      "name": "__alloc_workqueue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1114
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
struct workqueue_struct * __alloc_workqueue_key(const char * fmt, unsigned int flags, int max_active, struct lock_class_key * key, const char * lock_name, void (anon))
```

```json
{
  "name": "__alloc_workqueue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539056,
      "name": "__alloc_workqueue_key",
      "external": true,
      "loc": "kernel/workqueue.c:3943",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:default_bdi_init",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/ext4/super.c:ext4_fill_super",
        "crypto/crypto_wq.c:crypto_wq_init",
        "block/bio.c:bioset_create",
        "block/blk-core.c:blk_dev_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "net/core/net_namespace.c:net_ns_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539056,
      "name": "__alloc_workqueue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
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
struct workqueue_struct * __alloc_workqueue_key(const char * fmt, unsigned int flags, int max_active, struct lock_class_key * key, const char * lock_name, void (anon))
```

```json
{
  "name": "__alloc_workqueue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565472,
      "name": "__alloc_workqueue_key",
      "external": true,
      "loc": "kernel/workqueue.c:4047",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/power/main.c:pm_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/cgroup/cgroup.c:cgroup_wq_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_wq_init",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:cgwb_init",
        "mm/backing-dev.c:default_bdi_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/ext4/super.c:ext4_fill_super",
        "crypto/crypto_wq.c:crypto_wq_init",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565472,
      "name": "__alloc_workqueue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
struct workqueue_struct * __alloc_workqueue_key(const char * fmt, unsigned int flags, int max_active, struct lock_class_key * key, const char * lock_name, void (anon))
```

```json
{
  "name": "__alloc_workqueue_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579602704,
      "name": "__alloc_workqueue_key",
      "external": true,
      "loc": "kernel/workqueue.c:4070",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/power/main.c:pm_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/cgroup/cgroup.c:cgroup_wq_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_wq_init",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:cgwb_init",
        "mm/backing-dev.c:default_bdi_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/ext4/super.c:ext4_fill_super",
        "crypto/crypto_wq.c:crypto_wq_init",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602704,
      "name": "__alloc_workqueue_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
    }
  ]
}
```
</details>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct workqueue_struct * __alloc_workqueue_key(const char * fmt, unsigned int flags, int max_active, struct lock_class_key * key, const char * lock_name, void (anon))
```
</details>
</li>
</ul>
