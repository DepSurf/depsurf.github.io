# Function: <code>flush_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579479648,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:2742",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:workqueue_cpu_down_callback",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/padata.c:padata_flush_queues",
        "kernel/padata.c:padata_flush_queues",
        "mm/swap.c:lru_add_drain_all",
        "mm/swapfile.c:SyS_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev.c:tpm_release",
        "drivers/char/tpm/tpm-dev.c:tpm_read",
        "drivers/base/node.c:node_device_release",
        "drivers/block/virtio_blk.c:virtblk_freeze",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/xen-blkfront.c:xlvbd_release_gendisk",
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/net/virtio_net.c:virtnet_freeze",
        "drivers/net/virtio_net.c:virtnet_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479648,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493472,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:2842",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/padata.c:padata_flush_queues",
        "kernel/padata.c:padata_flush_queues",
        "mm/swap.c:lru_add_drain_all",
        "mm/swapfile.c:SyS_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev.c:tpm_release",
        "drivers/char/tpm/tpm-dev.c:tpm_read",
        "drivers/base/node.c:node_device_release",
        "drivers/block/virtio_blk.c:virtblk_freeze",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/virtio_net.c:virtnet_freeze",
        "drivers/net/virtio_net.c:virtnet_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493472,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512768,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:2847",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/padata.c:padata_flush_queues",
        "kernel/padata.c:padata_flush_queues",
        "mm/swap.c:lru_add_drain_all",
        "mm/swapfile.c:SyS_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev.c:tpm_release",
        "drivers/char/tpm/tpm-dev.c:tpm_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512768,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501248,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:2846",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/padata.c:padata_flush_queues",
        "kernel/padata.c:padata_flush_queues",
        "mm/swapfile.c:SyS_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501248,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527248,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:2863",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/padata.c:padata_flush_queues",
        "kernel/padata.c:padata_flush_queues",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swapfile.c:SYSC_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/pci/pcie/aer/aerdrv.c:aer_remove",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527248,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579555698,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:2936",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/padata.c:padata_flush_queues",
        "kernel/padata.c:padata_flush_queues",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swap.c:lru_add_drain_all",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/pci/pcie/aer.c:aer_remove",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555488,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579593314,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:2959",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/padata.c:padata_flush_queues",
        "kernel/padata.c:padata_flush_queues",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swap.c:lru_add_drain_all",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593104,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579618990,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3059",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/padata.c:padata_flush_queues",
        "kernel/padata.c:padata_flush_queues",
        "mm/swap.c:lru_add_drain_all",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618784,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579642670,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3068",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:lru_add_drain_all",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:brightness_store",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642464,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579673265,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3065",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:lru_add_drain_all",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_suspend",
        "drivers/leds/led-class.c:brightness_store",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668416,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579653089,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3071",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:lru_add_drain_all",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_suspend",
        "drivers/leds/led-class.c:brightness_store",
        "net/core/dev.c:flush_all_backlogs",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648304,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579659473,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3072",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:__lru_add_drain_all",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_suspend",
        "drivers/leds/led-class.c:brightness_store",
        "net/core/dev.c:flush_all_backlogs",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654496,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579736449,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3111",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:__lru_add_drain_all",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/slub.c:flush_all_cpus_locked",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/ext4/balloc.c:ext4_should_retry_alloc",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_suspend",
        "drivers/leds/led-class.c:brightness_store",
        "net/core/dev.c:flush_all_backlogs",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731376,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579842158,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3094",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:__lru_add_drain_all",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/slub.c:flush_all_cpus_locked",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/ext4/balloc.c:ext4_should_retry_alloc",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:led_suspend",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/hte/hte.c:hte_ts_put",
        "net/core/dev.c:flush_all_backlogs",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842000,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579979950,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3092",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:__lru_add_drain_all",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/slub.c:flush_all_cpus_locked",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/ext4/balloc.c:ext4_should_retry_alloc",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_load_and_init_journal",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:led_suspend",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/hte/hte.c:hte_ts_put",
        "net/core/dev.c:flush_all_backlogs",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973296,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580029054,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3408",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/watchdog.c:lockup_detector_check",
        "mm/swap.c:__lru_add_drain_all",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/slub.c:flush_all_cpus_locked",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/ext4/balloc.c:ext4_should_retry_alloc",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_load_and_init_journal",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_unregister",
        "drivers/block/virtio_blk.c:virtblk_freeze",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/virtio_net.c:virtnet_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:led_suspend",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/hte/hte.c:hte_ts_put",
        "net/core/dev.c:flush_all_backlogs",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580023984,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071982,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3429",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe_key",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/watchdog.c:lockup_detector_check",
        "mm/swap.c:__lru_add_drain_all",
        "mm/slub.c:flush_all_cpus_locked",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/ext4/balloc.c:ext4_should_retry_alloc",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_load_and_init_journal",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_release_struct",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_io.c:tty_kclose",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_unregister",
        "drivers/block/virtio_blk.c:virtblk_freeze",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/gpu/drm/drm_framebuffer.c:drm_fb_release",
        "drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb",
        "drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup",
        "drivers/net/virtio_net.c:virtnet_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:stop_sync_thread",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:led_suspend",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/hte/hte.c:hte_ts_put",
        "net/core/dev.c:flush_all_backlogs",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067792,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490809588,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3068",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_rcu_work",
        "kernel/workqueue.c:flush_rcu_work",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "virt/kvm/eventfd.c:irqfd_shutdown",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:lru_add_drain_all",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/mmc/core/queue.c:mmc_cleanup_queue",
        "drivers/leds/led-class.c:brightness_store",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490805792,
      "name": "flush_work",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224844524,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3068",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:lru_add_drain_all",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/omap-serial.c:serial_omap_suspend",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/gadget/udc/core.c:usb_del_gadget_udc",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/mmc/core/queue.c:mmc_cleanup_queue",
        "drivers/leds/led-class.c:brightness_store",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224844288,
      "name": "flush_work",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283645564,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3068",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_rcu_work",
        "kernel/workqueue.c:flush_rcu_work",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:lru_add_drain_all",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/hvc/hvsi.c:hvsi_close",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:brightness_store",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283645232,
      "name": "flush_work",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271484964,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3068",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_rcu_work",
        "kernel/workqueue.c:flush_rcu_work",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:lru_add_drain_all",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/mmc/core/queue.c:mmc_cleanup_queue",
        "drivers/leds/led-class.c:brightness_store",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271483372,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579618974,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3068",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:lru_add_drain_all",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkfront_freeze",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/nvme/host/core.c:nvme_stop_ctrl",
        "drivers/nvme/host/core.c:nvme_remove_namespaces",
        "drivers/nvme/host/core.c:nvme_do_delete_ctrl",
        "drivers/nvme/host/multipath.c:nvme_mpath_remove_disk",
        "drivers/nvme/host/pci.c:nvme_error_resume",
        "drivers/nvme/host/pci.c:nvme_remove",
        "drivers/nvme/host/pci.c:nvme_reset_done",
        "drivers/nvme/host/pci.c:nvme_async_probe",
        "drivers/nvme/host/pci.c:nvme_async_probe",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618768,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579547358,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3068",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:lru_add_drain_all",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/nvme/host/core.c:nvme_stop_ctrl",
        "drivers/nvme/host/core.c:nvme_remove_namespaces",
        "drivers/nvme/host/core.c:nvme_do_delete_ctrl",
        "drivers/nvme/host/multipath.c:nvme_mpath_remove_disk",
        "drivers/nvme/host/pci.c:nvme_error_resume",
        "drivers/nvme/host/pci.c:nvme_remove",
        "drivers/nvme/host/pci.c:nvme_reset_done",
        "drivers/nvme/host/pci.c:nvme_async_probe",
        "drivers/nvme/host/pci.c:nvme_async_probe",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547168,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579616254,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3068",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:lru_add_drain_all",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:brightness_store",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616048,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool flush_work(struct work_struct * work)
```

```json
{
  "name": "flush_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579649838,
      "name": "flush_work",
      "external": true,
      "loc": "kernel/workqueue.c:3068",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu",
        "kernel/workqueue.c:schedule_on_each_cpu",
        "kernel/workqueue.c:flush_delayed_work"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/swap.c:lru_add_drain_all",
        "mm/page_alloc.c:drain_all_pages",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/vmpressure.c:vmpressure_cleanup",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/pstore/platform.c:pstore_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_io.c:tty_flush_works",
        "drivers/tty/tty_buffer.c:tty_buffer_flush_work",
        "drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_timeout_work_func",
        "drivers/base/node.c:node_device_release",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/md/dm-stripe.c:stripe_dtr",
        "drivers/leds/led-class.c:brightness_store",
        "net/core/dev.c:rollback_registered_many",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_flush_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644976,
      "name": "flush_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
