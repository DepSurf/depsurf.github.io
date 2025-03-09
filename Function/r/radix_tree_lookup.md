# Function: <code>radix_tree_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * radix_tree_lookup(struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582969856,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:573",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/filemap.c:page_cache_next_hole",
        "mm/filemap.c:page_cache_prev_hole",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582969856,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583258560,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:743",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/memremap.c:to_vmem_altmap",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/filemap.c:page_cache_prev_hole",
        "mm/filemap.c:page_cache_next_hole",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258560,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375200,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:977",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/memremap.c:to_vmem_altmap",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/filemap.c:page_cache_prev_hole",
        "mm/filemap.c:page_cache_next_hole",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375200,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588224624,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:1097",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/memremap.c:to_vmem_altmap",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/filemap.c:page_cache_prev_hole",
        "mm/filemap.c:page_cache_next_hole",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock",
        "ipc/util.c:ipc_get_maxid",
        "ipc/namespace.c:free_ipcs",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pwm/core.c:pwm_request",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_find_get",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588224624,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588774688,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:1096",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/memremap.c:to_vmem_altmap",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/filemap.c:page_cache_prev_hole",
        "mm/filemap.c:page_cache_next_hole",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/hmm.c:hmm_devmem_pages_create",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pwm/core.c:pwm_request",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_find_get",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/act_api.c:tcf_idr_check",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588774688,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589153328,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:1097",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/memremap.c:get_dev_pagemap",
        "mm/filemap.c:page_cache_prev_hole",
        "mm/filemap.c:page_cache_next_hole",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/hmm.c:hmm_devmem_pages_create",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_lookup_slowpath",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589153328,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589385872,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:839",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_lookup_slowpath",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589385872,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589842880,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:826",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_lookup_slowpath",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589842880,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590068976,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:826",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_lookup_slowpath",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590068976,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066128,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:818",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:per_cpu_count_show",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:cgwb_create",
        "mm/vmalloc.c:vb_free",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "lib/idr.c:idr_find",
        "drivers/pinctrl/core.c:pinctrl_groups_show",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_register_one_pin",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "net/mptcp/token.c:mptcp_token_get_sock",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/token.c:mptcp_token_new_request",
        "net/mptcp/token.c:mptcp_token_new_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066128,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585215456,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:818",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "lib/idr.c:idr_find",
        "drivers/pinctrl/core.c:pinctrl_groups_show",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_register_one_pin",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215456,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585098304,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:818",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "lib/idr.c:idr_find",
        "drivers/pinctrl/core.c:pinctrl_groups_show",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585098304,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585546560,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:818",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:__irq_resolve_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "lib/idr.c:idr_find",
        "drivers/pinctrl/core.c:pinctrl_groups_show",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585546560,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702272,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:818",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq_safe",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:__irq_resolve_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "lib/idr.c:idr_find",
        "drivers/pinctrl/core.c:pinctrl_groups_show",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702272,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595863984,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:818",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq_safe",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:__irq_resolve_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:blk_throtl_cancel_bios",
        "block/blk-throttle.c:tg_conf_updated",
        "drivers/pinctrl/core.c:pinctrl_groups_show",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_set_mux",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595863984,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596381328,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:817",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_resolve_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:blk_throtl_cancel_bios",
        "block/blk-throttle.c:tg_conf_updated",
        "drivers/pinctrl/core.c:pinctrl_groups_show",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_set_mux",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596381328,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597276576,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:817",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_resolve_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:blk_throtl_cancel_bios",
        "block/blk-throttle.c:tg_conf_updated",
        "drivers/pinctrl/core.c:pinctrl_groups_show",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_register_pins",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_set_mux",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597276576,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503846912,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:826",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_lookup_slowpath",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_generic_remove_group",
        "drivers/pinctrl/core.c:pinctrl_generic_get_group",
        "drivers/pinctrl/core.c:pinctrl_generic_get_group_name",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_generic_remove_function",
        "drivers/pinctrl/pinmux.c:pinmux_generic_get_function",
        "drivers/pinctrl/pinmux.c:pinmux_generic_get_function_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pinctrl/pinctrl-single.c:pcs_get_function",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503846912,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236466440,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:826",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_lookup_slowpath",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_generic_remove_group",
        "drivers/pinctrl/core.c:pinctrl_generic_get_group",
        "drivers/pinctrl/core.c:pinctrl_generic_get_group_name",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_generic_remove_function",
        "drivers/pinctrl/pinmux.c:pinmux_generic_get_function",
        "drivers/pinctrl/pinmux.c:pinmux_generic_get_function_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pinctrl/pinctrl-single.c:pcs_get_function",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_set",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_set",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_input_enable",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_get",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_get",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_get_drvctrl_data",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/usb/host/xhci-mem.c:xhci_remove_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236466440,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297700960,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:826",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_lookup_slowpath",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_generic_remove_group",
        "drivers/pinctrl/core.c:pinctrl_generic_get_group",
        "drivers/pinctrl/core.c:pinctrl_generic_get_group_name",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_generic_remove_function",
        "drivers/pinctrl/pinmux.c:pinmux_generic_get_function",
        "drivers/pinctrl/pinmux.c:pinmux_generic_get_function_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pinctrl/pinctrl-single.c:pcs_get_function",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297700960,
      "name": "radix_tree_lookup",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279736896,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:826",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_lookup_slowpath",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_generic_remove_group",
        "drivers/pinctrl/core.c:pinctrl_generic_get_group",
        "drivers/pinctrl/core.c:pinctrl_generic_get_group_name",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_generic_remove_function",
        "drivers/pinctrl/pinmux.c:pinmux_generic_get_function",
        "drivers/pinctrl/pinmux.c:pinmux_generic_get_function_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-single.c:pcs_get_function",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279736896,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671232,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:826",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_lookup_slowpath",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589671232,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589397056,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:826",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_lookup_slowpath",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589397056,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590114608,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:826",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_lookup_slowpath",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590114608,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * radix_tree_lookup(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590164992,
      "name": "radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:826",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:kstat_irqs",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_unmap_ram",
        "block/blk-ioc.c:ioc_lookup_icq",
        "block/blk-cgroup.c:blkg_lookup_slowpath",
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_free_pindescs",
        "drivers/pinctrl/core.c:pin_get_from_name",
        "drivers/pinctrl/pinmux.c:pinmux_pins_show",
        "drivers/pinctrl/pinmux.c:pinmux_disable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pinmux_enable_setting",
        "drivers/pinctrl/pinmux.c:pin_free",
        "drivers/pinctrl/pinmux.c:pin_request",
        "drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio",
        "drivers/pinctrl/pinconf.c:pinconf_pins_show",
        "drivers/pinctrl/pinconf.c:pinconf_show_setting",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save",
        "drivers/pwm/core.c:pwm_request",
        "drivers/usb/host/xhci-mem.c:xhci_dma_to_transfer_ring",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "lib/idr.c:idr_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590164992,
      "name": "radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root * root</code> ➡️ <code>const struct radix_tree_root * root</code>
</li>
</ul>
</details>
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
<code>const struct radix_tree_root * root</code> ➡️ <code>const struct xarray * root</code>
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
