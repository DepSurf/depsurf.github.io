# Function: <code>destroy_workqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473152,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:3910",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/crypto.c:ext4_exit_crypto",
        "crypto/crypto_wq.c:crypto_wq_exit",
        "block/bio.c:bioset_free",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/block/virtio_blk.c:fini",
        "drivers/block/virtio_blk.c:init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/mmc/core/core.c:mmc_exit",
        "drivers/mmc/core/core.c:mmc_init",
        "drivers/devfreq/devfreq.c:devfreq_exit",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473152,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579486848,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4008",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "crypto/crypto_wq.c:crypto_wq_exit",
        "block/bio.c:bioset_free",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/block/virtio_blk.c:fini",
        "drivers/block/virtio_blk.c:init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/charger-manager.c:charger_manager_cleanup",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486848,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579521088,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4036",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "crypto/crypto_wq.c:crypto_wq_exit",
        "block/bio.c:bioset_free",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521088,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509184,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4055",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "crypto/crypto_wq.c:crypto_wq_exit",
        "block/bio.c:bioset_free",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509184,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535952,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4066",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "crypto/crypto_wq.c:crypto_wq_exit",
        "block/bio.c:bioset_free",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_mod_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535952,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562176,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4149",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "crypto/crypto_wq.c:crypto_wq_exit",
        "block/bio.c:bioset_exit",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_mod_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562176,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599408,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4172",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "crypto/crypto_wq.c:crypto_wq_exit",
        "block/bio.c:bioset_exit",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/strparser/strparser.c:strp_mod_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599408,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4314",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628802,
      "name": "destroy_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071579622736,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579648672,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4332",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/io_uring.c:io_finish_async",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/vfio/virqfd.c:vfio_virqfd_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648672,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4357",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/padata.c:__padata_free",
        "kernel/padata.c:__padata_free",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/vfio/virqfd.c:vfio_virqfd_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685491,
      "name": "destroy_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071579680528,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4370",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/trace/trace.c:trace_eval_sync",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/vfio/virqfd.c:vfio_virqfd_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591280852,
      "name": "destroy_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071579660368,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4377",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/trace/trace.c:trace_eval_sync",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/vfio/virqfd.c:vfio_virqfd_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/mcast.c:igmp6_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591223801,
      "name": "destroy_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071579666416,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4416",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/trace/trace.c:trace_eval_sync",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/iommu/io-pgfault.c:iopf_queue_free",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/vfio/virqfd.c:vfio_virqfd_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/mcast.c:igmp6_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592104983,
      "name": "destroy_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071579743216,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579847424,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4399",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/trace/ftrace.c:ftrace_check_sync",
        "kernel/trace/trace.c:trace_eval_sync",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:init_zswap",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/iommu/io-pgfault.c:iopf_queue_free",
        "drivers/block/loop.c:lo_free_disk",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/vfio/virqfd.c:vfio_virqfd_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/mcast.c:igmp6_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579847424,
      "name": "destroy_workqueue",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987840,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4408",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/trace/ftrace.c:ftrace_check_sync",
        "kernel/trace/trace.c:trace_eval_sync",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/pci/doe.c:pcim_doe_create_mb",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/iommu/io-pgfault.c:iopf_queue_free",
        "drivers/block/loop.c:lo_free_disk",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/mcast.c:igmp6_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987840,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580040976,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4741",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/trace/ftrace.c:ftrace_check_sync",
        "kernel/trace/trace.c:trace_eval_sync",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:zswap_setup",
        "mm/zswap.c:zswap_setup",
        "fs/super.c:sb_init_dio_done_wq",
        "fs/super.c:generic_shutdown_super",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/pci/doe.c:pci_doe_destroy",
        "drivers/pci/doe.c:pci_doe_init",
        "drivers/pci/doe.c:pci_doe_create_mb",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/iommu/io-pgfault.c:iopf_queue_free",
        "drivers/block/loop.c:lo_free_disk",
        "drivers/block/virtio_blk.c:virtio_blk_fini",
        "drivers/block/virtio_blk.c:virtio_blk_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-stripe.c:dm_stripe_exit",
        "drivers/md/dm-stripe.c:dm_stripe_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/mcast.c:igmp6_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040976,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580083600,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4776",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/trace/ftrace.c:ftrace_check_sync",
        "kernel/trace/trace.c:trace_eval_sync",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:sb_init_dio_done_wq",
        "fs/super.c:generic_shutdown_super",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_core.c:init_slots",
        "drivers/pci/doe.c:pci_doe_destroy",
        "drivers/pci/doe.c:pci_doe_init",
        "drivers/pci/doe.c:pci_doe_create_mb",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/iommu/io-pgfault.c:iopf_queue_free",
        "drivers/block/loop.c:lo_free_disk",
        "drivers/block/virtio_blk.c:virtio_blk_fini",
        "drivers/block/virtio_blk.c:virtio_blk_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-stripe.c:dm_stripe_exit",
        "drivers/md/dm-stripe.c:dm_stripe_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/remoteproc/remoteproc_core.c:remoteproc_exit",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/mcast.c:igmp6_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083600,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490820920,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4332",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/eventfd.c:kvm_irqfd_exit",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/io_uring.c:io_finish_async",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490820920,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224854296,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4332",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/io_uring.c:io_finish_async",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/host/sdhci.c:sdhci_remove_host",
        "drivers/mmc/host/sdhci.c:__sdhci_add_host",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224854296,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283654624,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4332",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/io_uring.c:io_finish_async",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/vfio/virqfd.c:vfio_virqfd_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283654624,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271495080,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4332",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/io_uring.c:io_finish_async",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271495080,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624976,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4332",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/io_uring.c:io_finish_async",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/nvme/host/core.c:nvme_core_exit",
        "drivers/nvme/host/core.c:nvme_core_exit",
        "drivers/nvme/host/core.c:nvme_core_exit",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624976,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579553344,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4332",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/io_uring.c:io_finish_async",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/nfit/core.c:nfit_exit",
        "drivers/acpi/nfit/core.c:nfit_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_transport_fc.c:fc_remove_host",
        "drivers/scsi/scsi_transport_fc.c:fc_remove_host",
        "drivers/scsi/scsi_transport_fc.c:fc_host_setup",
        "drivers/scsi/storvsc_drv.c:storvsc_remove",
        "drivers/scsi/storvsc_drv.c:storvsc_probe",
        "drivers/nvme/host/core.c:nvme_core_exit",
        "drivers/nvme/host/core.c:nvme_core_exit",
        "drivers/nvme/host/core.c:nvme_core_exit",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/vfio/virqfd.c:vfio_virqfd_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/hv/connection.c:vmbus_disconnect",
        "drivers/hv/connection.c:vmbus_disconnect",
        "drivers/hv/connection.c:vmbus_disconnect",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553344,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622256,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4332",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/io_uring.c:io_finish_async",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/vfio/virqfd.c:vfio_virqfd_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622256,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
void destroy_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "destroy_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655936,
      "name": "destroy_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:4332",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "fs/super.c:generic_shutdown_super",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/io_uring.c:io_finish_async",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/verify.c:fsverity_exit_workqueue",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio.c:bioset_exit",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/thermal.c:acpi_thermal_exit",
        "drivers/acpi/thermal.c:acpi_thermal_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/ata/libata-sff.c:ata_sff_exit",
        "drivers/vfio/virqfd.c:vfio_virqfd_exit",
        "drivers/usb/core/hub.c:usb_hub_cleanup",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/power/supply/charger-manager.c:charger_manager_cleanup",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "net/sched/cls_api.c:tc_filter_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655936,
      "name": "destroy_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
