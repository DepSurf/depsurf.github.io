# Function: <code>wait_for_completion</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587368352,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:120",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_notify",
        "kernel/kmod.c:call_usermodehelper_exec",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_work",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:kthread_create_on_node",
        "kernel/kthread.c:flush_kthread_worker",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:flush_kthread_work",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcu.c:__synchronize_srcu",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/stop_machine.c:stop_two_cpus",
        "fs/aio.c:exit_aio",
        "fs/aio.c:SyS_io_destroy",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/crypto.c:ext4_page_crypto",
        "fs/ext4/crypto_key.c:ext4_derive_key_aes",
        "fs/ext4/crypto_fname.c:ext4_fname_encrypt",
        "fs/ext4/crypto_fname.c:ext4_fname_decrypt",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/integrity/ima/ima_crypto.c:ahash_wait",
        "block/bio.c:submit_bio_wait",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "net/core/flow.c:flow_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587368352,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587869168,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:120",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/kmod.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:flush_kthread_worker",
        "kernel/kthread.c:flush_kthread_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcu.c:__synchronize_srcu",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/integrity/ima/ima_crypto.c:ahash_wait",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "net/core/flow.c:flow_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587869168,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588083728,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:120",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/kmod.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcu.c:__synchronize_srcu",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/integrity/ima/ima_crypto.c:ahash_wait",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "net/core/flow.c:flow_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588083728,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588310576,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:123",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/kmod.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ahash_wait",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_areq",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "net/core/flow.c:flow_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588310576,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588876032,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:137",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "mm/hmm.c:hmm_devmem_ref_kill",
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_areq",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588876032,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589254432,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:134",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "mm/hmm.c:hmm_devmem_ref_kill",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589254432,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589496656,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:134",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/livepatch/core.c:klp_register_patch",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "mm/hmm.c:hmm_devmem_ref_exit",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589496656,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589957440,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:134",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/livepatch/core.c:klp_free_patch_finish",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589957440,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590185104,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:134",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/livepatch/core.c:klp_free_patch_finish",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590185104,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591203504,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:136",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_invoke_ap_callback",
        "kernel/cpu.c:cpuhp_invoke_ap_callback",
        "kernel/cpu.c:bringup_wait_for_ap",
        "kernel/cpu.c:cpuhp_kick_ap",
        "kernel/cpu.c:cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_patch_work_fn",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_init",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sq_offload_start",
        "fs/io_uring.c:io_sqe_files_unregister",
        "fs/io-wq.c:__io_wq_destroy",
        "fs/io-wq.c:io_wq_create",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:coredump_wait",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/debugfs/inode.c:remove_one",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591203504,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591698640,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:136",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_invoke_ap_callback",
        "kernel/cpu.c:cpuhp_invoke_ap_callback",
        "kernel/cpu.c:bringup_wait_for_ap",
        "kernel/cpu.c:cpuhp_kick_ap",
        "kernel/cpu.c:cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_patch_work_fn",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_init",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:io_sq_thread_stop",
        "fs/io-wq.c:__io_wq_destroy",
        "fs/io-wq.c:io_wq_create",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:coredump_wait",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/debugfs/inode.c:remove_one",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591698640,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591641152,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:136",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_patch_work_fn",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sq_thread_finish",
        "fs/io-wq.c:io_wq_exit_workers",
        "fs/io-wq.c:io_wqe_worker",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:coredump_wait",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/debugfs/inode.c:remove_one",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591641152,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592815072,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:136",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_patch_work_fn",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:lockup_detector_offline_cpu",
        "kernel/watchdog.c:softlockup_stop_fn",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wqe_worker",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:coredump_wait",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/debugfs/inode.c:remove_one",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/devlink.c:devlink_unregister",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592815072,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594717232,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:136",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_patch_work_fn",
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:lockup_detector_offline_cpu",
        "kernel/watchdog.c:softlockup_stop_fn",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:coredump_wait",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/debugfs/inode.c:remove_one",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:io_wait_rsrc_data",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wqe_worker",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/devlink.c:devlink_unregister",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594717232,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596464928,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:136",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_patch_work_fn",
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:lockup_detector_offline_cpu",
        "kernel/watchdog.c:softlockup_stop_fn",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/debugfs/inode.c:remove_one",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/sqpoll.c:io_sq_thread_stop",
        "io_uring/rsrc.c:io_wait_rsrc_data",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wqe_worker",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/pci/doe.c:pci_doe_discovery",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/devlink.c:devlink_unregister",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596464928,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597007840,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:136",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_bringup_ap",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/vhost_task.c:vhost_task_stop",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_patch_work_fn",
        "kernel/module/main.c:idempotent_init_module",
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:lockup_detector_offline_cpu",
        "kernel/watchdog.c:softlockup_stop_fn",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/debugfs/inode.c:remove_one",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/akcipher.c:crypto_akcipher_sync_post",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "io_uring/sqpoll.c:io_sq_thread_stop",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_worker",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/pci/doe.c:pci_doe",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/md/md-bitmap.c:md_bitmap_unplug_async",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597007840,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597936384,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:146",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_bringup_ap",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/vhost_task.c:vhost_task_stop",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_free_patch_work_fn",
        "kernel/module/main.c:idempotent_init_module",
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:lockup_detector_offline_cpu",
        "kernel/watchdog.c:softlockup_stop_fn",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/shrinker.c:shrinker_free",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:__zswap_load",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/crypto.c:fscrypt_crypt_data_unit",
        "fs/crypto/crypto.c:fscrypt_crypt_data_unit",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "fs/debugfs/inode.c:remove_one",
        "fs/debugfs/inode.c:remove_one",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/akcipher.c:crypto_akcipher_sync_post",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "io_uring/sqpoll.c:io_sq_thread_stop",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_worker",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/pci/doe.c:pci_doe",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/iommu/intel/svm.c:intel_drain_pasid_prq",
        "drivers/iommu/intel/svm.c:intel_drain_pasid_prq",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/md/md-bitmap.c:md_bitmap_unplug_async",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:__efi_queue_work",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597936384,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503929392,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:134",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "virt/kvm/kvm_main.c:kvm_vm_create_worker_thread",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "fs/aio.c:__arm64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:__arm64_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "drivers/firmware/imx/imx-scu.c:imx_scu_call_rpc",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503929392,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236541124,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:134",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "arch/arm/common/bL_switcher.c:bL_switcher_active_store",
        "arch/arm/common/bL_switcher.c:bL_switch_to",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "fs/aio.c:__se_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf_irq_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_read_buf_irq_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref",
        "drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "drivers/firmware/imx/imx-scu.c:imx_scu_call_rpc",
        "sound/core/init.c:snd_card_free",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236541124,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297781280,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:134",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/livepatch/core.c:klp_free_patch_finish",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/watchdog.c:watchdog_disable",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:__se_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297781280,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279799744,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:134",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "fs/aio.c:__se_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279799744,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589787392,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:134",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/livepatch/core.c:klp_free_patch_finish",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589787392,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589509936,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:134",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/livepatch/core.c:klp_free_patch_finish",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "drivers/hv/vmbus_drv.c:vmbus_bus_suspend",
        "drivers/hv/connection.c:vmbus_negotiate_version",
        "drivers/hv/channel.c:vmbus_disconnect_ring",
        "drivers/hv/channel.c:vmbus_teardown_gpadl",
        "drivers/hv/channel.c:vmbus_establish_gpadl",
        "drivers/hv/channel.c:__vmbus_open",
        "drivers/hv/channel_mgmt.c:vmbus_initiate_unload",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589509936,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590230800,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:134",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/livepatch/core.c:klp_free_patch_finish",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590230800,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void wait_for_completion(struct completion * x)
```

```json
{
  "name": "wait_for_completion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590283440,
      "name": "wait_for_completion",
      "external": true,
      "loc": "kernel/sched/completion.c:134",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:__cpuhp_kick_ap",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:__flush_work",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_park",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/livepatch/core.c:klp_free_patch_finish",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/module.c:mod_kobject_put",
        "kernel/acct.c:acct_pin_kill",
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_disable",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_finish_async",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:do_coredump",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:close_pdeo",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/fuse/file.c:fuse_direct_IO",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/property.c:acpi_destroy_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node",
        "drivers/base/power/main.c:dpm_wait",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/dm-sysfs.c:dm_sysfs_exit",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590283440,
      "name": "wait_for_completion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
