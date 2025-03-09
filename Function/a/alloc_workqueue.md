# Function: <code>alloc_workqueue</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625984,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4211",
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
        "fs/io_uring.c:io_uring_create",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
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
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625984,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1096
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
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579652016,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4229",
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
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/vfio/virqfd.c:vfio_virqfd_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652016,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683280,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4238",
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
        "kernel/trace/trace.c:latency_fsnotify_init",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:cgwb_init",
        "mm/backing-dev.c:default_bdi_init",
        "mm/zswap.c:init_zswap",
        "mm/memcontrol.c:mem_cgroup_init",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/vfio/virqfd.c:vfio_virqfd_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_dev_init",
        "net/mptcp/pm.c:mptcp_pm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683280,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663184,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4251",
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
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:latency_fsnotify_init",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:cgwb_init",
        "mm/backing-dev.c:default_bdi_init",
        "mm/zswap.c:init_zswap",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/vfio/virqfd.c:vfio_virqfd_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv4/inet_fragment.c:inet_frag_wq_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663184,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669984,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4258",
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
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:latency_fsnotify_init",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:cgwb_init",
        "mm/backing-dev.c:default_bdi_init",
        "mm/zswap.c:init_zswap",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/vfio/virqfd.c:vfio_virqfd_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv4/inet_fragment.c:inet_frag_wq_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669984,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4297",
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
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:latency_fsnotify_init",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:cgwb_init",
        "mm/backing-dev.c:default_bdi_init",
        "mm/zswap.c:init_zswap",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/iommu/io-pgfault.c:iopf_queue_alloc",
        "drivers/block/loop.c:loop_configure",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/vfio/virqfd.c:vfio_virqfd_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv4/inet_fragment.c:inet_frag_wq_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592105135,
      "name": "alloc_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579747040,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4280",
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
        "kernel/trace/ftrace.c:ftrace_check_for_weak_functions",
        "kernel/trace/trace.c:trace_eval_init",
        "kernel/trace/trace.c:latency_fsnotify_init",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:cgwb_init",
        "mm/backing-dev.c:default_bdi_init",
        "mm/zswap.c:init_zswap",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:__ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/iommu/io-pgfault.c:iopf_queue_alloc",
        "drivers/block/loop.c:loop_configure",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/vfio/virqfd.c:vfio_virqfd_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv4/inet_fragment.c:inet_frag_wq_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593872771,
      "name": "alloc_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579851328,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1282
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4289",
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
        "kernel/trace/ftrace.c:ftrace_check_for_weak_functions",
        "kernel/trace/trace.c:trace_eval_init",
        "kernel/trace/trace.c:latency_fsnotify_init",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:cgwb_init",
        "mm/backing-dev.c:default_bdi_init",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/slub.c:kmem_cache_init_late",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:__ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/pci/doe.c:pcim_doe_create_mb",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/iommu/io-pgfault.c:iopf_queue_alloc",
        "drivers/block/loop.c:loop_configure",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv4/inet_fragment.c:inet_frag_wq_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595976539,
      "name": "alloc_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579991936,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4622",
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
        "kernel/trace/ftrace.c:ftrace_check_for_weak_functions",
        "kernel/trace/trace.c:trace_eval_init",
        "kernel/trace/trace.c:latency_fsnotify_init",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:cgwb_init",
        "mm/backing-dev.c:default_bdi_init",
        "mm/zswap.c:zswap_setup",
        "mm/zswap.c:zswap_setup",
        "mm/slub.c:kmem_cache_init_late",
        "fs/super.c:sb_init_dio_done_wq",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:__ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_punt_bio_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/pci/doe.c:pci_doe_create_mb",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/iommu/io-pgfault.c:iopf_queue_alloc",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/virtio_blk.c:virtio_blk_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-stripe.c:dm_stripe_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv4/inet_fragment.c:inet_frag_wq_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596494282,
      "name": "alloc_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071580045728,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4662",
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
        "kernel/trace/ftrace.c:ftrace_check_for_weak_functions",
        "kernel/trace/trace.c:trace_eval_init",
        "kernel/trace/trace.c:latency_fsnotify_init",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:cgwb_init",
        "mm/backing-dev.c:default_bdi_init",
        "mm/slub.c:kmem_cache_init_late",
        "mm/zswap.c:zswap_setup",
        "mm/zswap.c:zswap_setup",
        "fs/super.c:sb_init_dio_done_wq",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:__ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_punt_bio_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/pci/doe.c:pci_doe_create_mb",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/iommu/io-pgfault.c:iopf_queue_alloc",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/virtio_blk.c:virtio_blk_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-stripe.c:dm_stripe_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv4/inet_fragment.c:inet_frag_wq_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/mcast.c:igmp6_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597391025,
      "name": "alloc_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071580088736,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490824872,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4229",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/eventfd.c:kvm_irqfd_init",
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
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/soc/fsl/qbman/qman.c:qman_wq_alloc",
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
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490824872,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224858016,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4229",
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
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/rapidio/rio.c:rio_init_mports",
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
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/mmc/host/sdhci.c:__sdhci_add_host",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224858016,
      "name": "alloc_workqueue",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283659872,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4229",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/dlpar.c:dlpar_workqueue_init",
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
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/vfio/virqfd.c:vfio_virqfd_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283659872,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1252
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
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271498308,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4229",
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
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_alloc_possible",
        "mm/vmstat.c:init_mm_internals",
        "mm/backing-dev.c:cgwb_init",
        "mm/backing-dev.c:default_bdi_init",
        "mm/memcontrol.c:mem_cgroup_init",
        "fs/fs-writeback.c:cgroup_writeback_init",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/rapidio/rio.c:rio_init_mports",
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
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271498308,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 986
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
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628320,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4229",
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
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628320,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556672,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4229",
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
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/nfit/core.c:nfit_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_transport_fc.c:fc_host_setup",
        "drivers/scsi/scsi_transport_fc.c:fc_host_setup",
        "drivers/scsi/storvsc_drv.c:storvsc_probe",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/vfio/virqfd.c:vfio_virqfd_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/hv/connection.c:vmbus_connect",
        "drivers/hv/connection.c:vmbus_connect",
        "drivers/hv/connection.c:vmbus_connect",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556672,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625600,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4229",
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
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/vfio/virqfd.c:vfio_virqfd_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625600,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```

```json
{
  "name": "alloc_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659248,
      "name": "alloc_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4229",
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
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_init_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_dev_init",
        "block/blk-cgroup.c:blkcg_init",
        "block/blk-throttle.c:throtl_init",
        "block/bio-integrity.c:bio_integrity_init",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/osl.c:acpi_os_initialize1",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_init",
        "drivers/vfio/virqfd.c:vfio_virqfd_init",
        "drivers/usb/core/hub.c:usb_hub_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/power/supply/charger-manager.c:charger_manager_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_setup",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "net/core/net_namespace.c:net_ns_init",
        "net/core/sock_diag.c:sock_diag_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659248,
      "name": "alloc_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct workqueue_struct * alloc_workqueue(const char * fmt, unsigned int flags, int max_active, void (anon))
```
</details>
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
