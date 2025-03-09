# Function: <code>__init_swait_queue_head</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661376,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:4",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661376,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685648,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:4",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685648,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671824,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:4",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671824,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702576,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:5",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702576,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579736816,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736816,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776496,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776496,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804160,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804160,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851728,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851728,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890608,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_queue_task",
        "kernel/fork.c:_do_fork",
        "kernel/cpu.c:cpuhp_create",
        "kernel/cpu.c:cpuhp_create",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/acct.c:acct_on",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_ring_ctx_alloc",
        "fs/io_uring.c:io_ring_ctx_alloc",
        "fs/io-wq.c:io_wq_create",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:coredump_wait",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/debugfs/file.c:debugfs_file_get",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/api.c:crypto_larval_alloc",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_sleep_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm-io.c:sync_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel",
        "net/ipv4/inet_fragment.c:inet_frags_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890608,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885232,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_queue_task",
        "kernel/fork.c:kernel_clone",
        "kernel/cpu.c:cpuhp_create",
        "kernel/cpu.c:cpuhp_create",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/acct.c:acct_on",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_ring_ctx_alloc",
        "fs/io_uring.c:io_ring_ctx_alloc",
        "fs/io-wq.c:io_wq_create",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:coredump_wait",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/debugfs/file.c:debugfs_file_get",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/api.c:crypto_larval_alloc",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_sleep_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/scsi/scsi_scan.c:scsi_prep_async_scan",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm-io.c:sync_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/ipv4/inet_fragment.c:inet_frags_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885232,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894416,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/fork.c:kernel_clone",
        "kernel/cpu.c:cpuhp_create",
        "kernel/cpu.c:cpuhp_create",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/acct.c:acct_on",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_get_sq_data",
        "fs/io_uring.c:io_rsrc_data_alloc",
        "fs/io_uring.c:io_ring_ctx_alloc",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:create_io_worker",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:coredump_wait",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/debugfs/file.c:debugfs_file_get",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/api.c:crypto_larval_alloc",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_sleep_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/vfio/vfio.c:vfio_init_group_dev",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm-io.c:sync_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/selftests.c:__net_test_loopback",
        "net/ipv4/inet_fragment.c:inet_frags_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894416,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009264,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/fork.c:kernel_clone",
        "kernel/cpu.c:cpuhp_create",
        "kernel/cpu.c:cpuhp_create",
        "kernel/workqueue.c:flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/acct.c:acct_on",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/swapfile.c:alloc_swap_info",
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_get_sq_data",
        "fs/io_uring.c:io_rsrc_data_alloc",
        "fs/io_uring.c:io_ring_ctx_alloc",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:create_io_worker",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:coredump_wait",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/debugfs/file.c:debugfs_file_get",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/api.c:crypto_larval_alloc",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_sleep_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/vfio/vfio.c:vfio_init_group_dev",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm-io.c:sync_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/selftests.c:__net_test_loopback",
        "net/core/devlink.c:devlink_alloc_ns",
        "net/ipv4/inet_fragment.c:inet_frags_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009264,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137216,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:6",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/fork.c:kernel_clone",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/workqueue.c:__flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:set_kthread_struct",
        "kernel/kthread.c:set_kthread_struct",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/acct.c:acct_on",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/swapfile.c:alloc_swap_info",
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:coredump_wait",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/debugfs/file.c:debugfs_file_get",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/api.c:crypto_larval_alloc",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:io_get_sq_data",
        "io_uring/io_uring.c:io_rsrc_data_alloc",
        "io_uring/io_uring.c:io_ring_ctx_alloc",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:create_io_worker",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_sleep_init",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/vfio/vfio.c:vfio_init_group_dev",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm-io.c:sync_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_request",
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
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/selftests.c:__net_test_loopback",
        "net/core/devlink.c:devlink_alloc_ns",
        "net/ipv4/inet_fragment.c:inet_frags_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137216,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311792,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:6",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/fork.c:kernel_clone",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/workqueue.c:__flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:set_kthread_struct",
        "kernel/kthread.c:set_kthread_struct",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/acct.c:acct_on",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/swapfile.c:alloc_swap_info",
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/coredump.c:coredump_wait",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/debugfs/file.c:debugfs_file_get",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/apparmor/notify.c:aa_do_notification",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/api.c:crypto_larval_alloc",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:io_ring_ctx_alloc",
        "io_uring/sqpoll.c:io_get_sq_data",
        "io_uring/rsrc.c:io_rsrc_data_alloc",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:create_io_worker",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_sleep_init",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm-io.c:sync_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_request",
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
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/selftests.c:__net_test_loopback",
        "net/core/devlink.c:devlink_alloc_ns",
        "net/ipv4/inet_fragment.c:inet_frags_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311792,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580378464,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:6",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/fork.c:kernel_clone",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/workqueue.c:__flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:set_kthread_struct",
        "kernel/kthread.c:set_kthread_struct",
        "kernel/vhost_task.c:vhost_task_create",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/module/main.c:idempotent_init_module",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/acct.c:acct_on",
        "kernel/stop_machine.c:cpu_stop_init_done",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/swapfile.c:alloc_swap_info",
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/coredump.c:coredump_wait",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/debugfs/file.c:debugfs_file_get",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/apparmor/notify.c:aa_do_notification",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/api.c:crypto_larval_alloc",
        "crypto/akcipher.c:crypto_akcipher_sync_prep",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:io_ring_ctx_alloc",
        "io_uring/sqpoll.c:io_get_sq_data",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:create_io_worker",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_sleep_init",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm-io.c:sync_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_request",
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
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/mailbox/mailbox.c:mbox_bind_client",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/selftests.c:__net_test_loopback",
        "net/ipv4/inet_fragment.c:inet_frags_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378464,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580436448,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:6",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/fork.c:kernel_clone",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/workqueue.c:__flush_workqueue",
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:set_kthread_struct",
        "kernel/kthread.c:set_kthread_struct",
        "kernel/vhost_task.c:vhost_task_create",
        "kernel/sched/core.c:affine_move_task",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic",
        "kernel/rcu/update.c:__wait_rcu_gp",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/module/main.c:idempotent_init_module",
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/acct.c:acct_on",
        "kernel/stop_machine.c:cpu_stop_init_done",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/padata.c:padata_do_multithreaded",
        "mm/shrinker.c:shrinker_register",
        "mm/swapfile.c:alloc_swap_info",
        "mm/zswap.c:zswap_cpu_comp_prepare",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:exit_aio",
        "fs/crypto/crypto.c:fscrypt_crypt_data_unit",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/coredump.c:coredump_wait",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/sysfs.c:ext4_register_sysfs",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/debugfs/file.c:debugfs_file_get",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/apparmor/notify.c:aa_do_notification",
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm",
        "crypto/api.c:crypto_larval_alloc",
        "crypto/akcipher.c:crypto_akcipher_sync_prep",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:io_ring_ctx_alloc",
        "io_uring/sqpoll.c:io_get_sq_data",
        "io_uring/io-wq.c:io_wq_create",
        "io_uring/io-wq.c:create_io_worker",
        "arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup",
        "drivers/xen/grant-table.c:gnttab_unmap_refs_sync",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node",
        "drivers/tty/serdev/core.c:serdev_device_alloc",
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/char/hw_random/core.c:hwrng_register",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/devtmpfs.c:devtmpfs_submit_req",
        "drivers/base/power/main.c:device_pm_sleep_init",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_device_init",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/ezx-pcap.c:pcap_adc_sync",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm-io.c:sync_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpuidle/sysfs.c:cpuidle_add_sysfs",
        "drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs",
        "drivers/mmc/core/core.c:mmc_wait_for_req",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/firmware/efi/runtime-wrappers.c:__efi_queue_work",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/mailbox/mailbox.c:mbox_bind_client",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/selftests.c:__net_test_loopback",
        "net/ipv4/inet_fragment.c:inet_frags_init",
        "net/packet/af_packet.c:packet_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436448,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491045480,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vcpu_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491045480,
      "name": "__init_swait_queue_head",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225052620,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225052620,
      "name": "__init_swait_queue_head",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283922704,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283922704,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271643380,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271643380,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824080,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824080,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758672,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758672,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812096,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812096,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_swait_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857232,
      "name": "__init_swait_queue_head",
      "external": true,
      "loc": "kernel/sched/swait.c:7",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857232,
      "name": "__init_swait_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void __init_swait_queue_head(struct swait_queue_head * q, const char * name, struct lock_class_key * key)
```
</details>
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
