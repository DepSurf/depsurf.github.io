# Function: <code>mutex_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587371408,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:900",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:worker_thread",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/rcu/tree.c:synchronize_sched_expedited",
        "kernel/kexec_core.c:crash_kexec",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec.c:compat_SyS_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/stop_machine.c:try_stop_cpus",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/memcontrol.c:try_charge",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/vme/vme.c:vme_dma_list_add",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_free",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587371408,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587872240,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:904",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:worker_thread",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec.c:compat_SyS_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587872240,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588087248,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1005",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:worker_thread",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec.c:compat_SyS_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588087248,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588313872,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1177",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:worker_thread",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:compat_SyS_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588313872,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588879360,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1177",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:compat_SyS_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588879360,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589257360,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1201",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589257360,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589499648,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1379",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589499648,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589960080,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1384",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589960080,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579907566,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1410",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:mutex_trylock_recursive"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590187744,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579951374,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1410",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:mutex_trylock_recursive"
      ],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:drain_all_pages",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "fs/dcache.c:d_splice_alias",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/aio.c:aio_migratepage",
        "drivers/pci/pci.c:pci_slot_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_uA_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/base/core.c:online_store",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591204032,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939790,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1413",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:mutex_trylock_recursive"
      ],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "fs/dcache.c:d_splice_alias",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/aio.c:aio_migratepage",
        "fs/io_uring.c:__io_uring_show_fdinfo",
        "drivers/pci/pci.c:pci_slot_trylock",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:destroy_regulator",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_uA_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/base/core.c:online_store",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591699168,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591641680,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1411",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "fs/dcache.c:d_splice_alias",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/aio.c:aio_migratepage",
        "fs/io_uring.c:__io_uring_show_fdinfo",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_uA_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/base/core.c:online_store",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591641680,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592815424,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1025",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg",
        "fs/dcache.c:d_splice_alias",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/aio.c:aio_migratepage",
        "fs/io_uring.c:__io_uring_show_fdinfo",
        "fs/io_uring.c:tctx_task_work",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/base/core.c:online_store",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592815424,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580212298,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1081",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:ww_mutex_trylock"
      ],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/page_alloc.c:__alloc_pages_may_oom",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg",
        "fs/dcache.c:d_splice_alias",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "io_uring/io_uring.c:__io_uring_show_fdinfo",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:handle_prev_tw_list",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/base/core.c:online_store",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594718832,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580405242,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1081",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:ww_mutex_trylock"
      ],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/page_alloc.c:__alloc_pages_may_oom",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg",
        "fs/dcache.c:d_splice_alias",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/aio.c:aio_migrate_folio",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "io_uring/io_uring.c:io_run_local_work",
        "io_uring/io_uring.c:handle_tw_list",
        "io_uring/io_uring.c:handle_tw_list",
        "io_uring/msg_ring.c:io_msg_ring",
        "io_uring/msg_ring.c:io_msg_install_complete",
        "io_uring/fdinfo.c:__io_uring_show_fdinfo",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/base/core.c:online_store",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/staging/vme_user/vme.c:vme_dma_free",
        "drivers/staging/vme_user/vme.c:vme_dma_list_free",
        "drivers/staging/vme_user/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock",
        "net/core/devlink.c:devl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596469056,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580474041,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1081",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:ww_mutex_trylock"
      ],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/page_alloc.c:__alloc_pages_may_oom",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg",
        "fs/dcache.c:d_splice_alias",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/aio.c:aio_migrate_folio",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "io_uring/io_uring.c:io_run_local_work",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/msg_ring.c:io_msg_install_complete",
        "io_uring/msg_ring.c:io_msg_ring_data",
        "io_uring/fdinfo.c:__io_uring_show_fdinfo",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/tty_io.c:do_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/base/core.c:online_store",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/staging/vme_user/vme.c:vme_dma_free",
        "drivers/staging/vme_user/vme.c:vme_dma_list_free",
        "drivers/staging/vme_user/vme.c:vme_dma_list_add",
        "drivers/platform/x86/intel/pmc/mtl.c:mtl_set_device_d3",
        "net/core/rtnetlink.c:rtnl_trylock",
        "net/devlink/core.c:devl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597010912,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580533865,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1086",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:ww_mutex_trylock"
      ],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/page_alloc.c:__alloc_pages_may_oom",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge_memcg",
        "fs/dcache.c:d_splice_alias",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/aio.c:aio_migrate_folio",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "io_uring/io_uring.c:io_run_local_work",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/msg_ring.c:io_msg_install_complete",
        "io_uring/msg_ring.c:io_msg_ring_data",
        "io_uring/fdinfo.c:io_uring_show_fdinfo",
        "drivers/pci/pci.c:__pci_reset_slot",
        "drivers/pci/pci.c:pci_bus_trylock",
        "drivers/pci/pci.c:pci_try_reset_function",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/tty/tty_io.c:tty_send_xchar",
        "drivers/tty/tty_io.c:iterate_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/base/core.c:online_store",
        "drivers/gpu/drm/drm_probe_helper.c:output_poll_execute",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/staging/vme_user/vme.c:vme_dma_free",
        "drivers/staging/vme_user/vme.c:vme_dma_list_free",
        "drivers/staging/vme_user/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock",
        "net/devlink/core.c:devlink_rel_nested_in_notify_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597940256,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491108268,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1410",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:mutex_trylock_recursive"
      ],
      "caller_func": [
        "virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_create",
        "virt/kvm/arm/vgic/vgic-kvm-device.c:lock_all_vcpus",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__arm64_compat_sys_kexec_load",
        "kernel/kexec.c:__arm64_sys_kexec_load",
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503930160,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225112256,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1410",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:mutex_trylock_recursive"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__se_sys_kexec_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev",
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "sound/core/pcm_native.c:snd_pcm_stream_group_ref",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236542208,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284000108,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1410",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:mutex_trylock_recursive"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__se_compat_sys_kexec_load",
        "kernel/kexec.c:__se_sys_kexec_load",
        "kernel/kexec_file.c:__se_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297782720,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271688906,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1410",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:mutex_trylock_recursive"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/clk/clk.c:clk_prepare_lock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279800274,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579879678,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1410",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:mutex_trylock_recursive"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589790032,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579814670,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1410",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:mutex_trylock_recursive"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589512512,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579867838,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1410",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:mutex_trylock_recursive"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590233440,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mutex_trylock(struct mutex * lock)
```

```json
{
  "name": "mutex_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579913262,
      "name": "mutex_trylock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1410",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:mutex_trylock_recursive"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/kexec_core.c:kernel_kexec",
        "kernel/kexec_core.c:__crash_kexec",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:try_stop_cpus",
        "mm/oom_kill.c:pagefault_out_of_memory",
        "mm/slab_common.c:dump_unreclaimable_slab",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:drain_all_pages",
        "fs/dcache.c:d_splice_alias",
        "fs/aio.c:aio_migratepage",
        "fs/ecryptfs/messaging.c:ecryptfs_send_message",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/tty/tty_io.c:tty_write_lock",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/spi/spi.c:spi_write_then_read",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/usb/core/usb.c:usb_lock_device_for_reset",
        "drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/vme/vme.c:vme_dma_free",
        "drivers/vme/vme.c:vme_dma_list_free",
        "drivers/vme/vme.c:vme_dma_list_add",
        "net/core/rtnetlink.c:rtnl_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590284224,
      "name": "mutex_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
