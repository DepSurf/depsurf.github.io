# Function: <code>cancel_work_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480704,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:2849",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "block/blk-mq.c:blk_mq_cancel_requeue_work",
        "block/blk-throttle.c:blk_throtl_exit",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/acpi/device_pm.c:acpi_remove_pm_notifier",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/power_supply_core.c:power_supply_unregister",
        "drivers/power/charger-manager.c:charger_manager_remove",
        "drivers/power/charger-manager.c:charger_extcon_notifier",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480704,
      "name": "cancel_work_sync",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494528,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:2949",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-mq.c:blk_mq_cancel_requeue_work",
        "block/blk-throttle.c:blk_throtl_exit",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/acpi/device_pm.c:acpi_remove_pm_notifier",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/power_supply_core.c:power_supply_unregister",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/power/charger-manager.c:charger_manager_remove",
        "drivers/power/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494528,
      "name": "cancel_work_sync",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513952,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:2963",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/acpi/device_pm.c:acpi_remove_pm_notifier",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:pm_genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513952,
      "name": "cancel_work_sync",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579502448,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:2962",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-throttle.c:blk_throtl_exit",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:pm_genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502448,
      "name": "cancel_work_sync",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528464,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:2976",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/bpf/sockmap.c:smap_gc_work",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-throttle.c:blk_throtl_exit",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:pm_genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528464,
      "name": "cancel_work_sync",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556224,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3038",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/bpf/sockmap.c:smap_gc_work",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-throttle.c:blk_throtl_exit",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:pm_genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556224,
      "name": "cancel_work_sync",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593840,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3061",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:pm_genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593840,
      "name": "cancel_work_sync",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579619536,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3161",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:pm_genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619536,
      "name": "cancel_work_sync",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643216,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3170",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:pm_genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643216,
      "name": "cancel_work_sync",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674880,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3167",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memory-failure.c:memory_failure_queue_kick",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/crc-t10dif.c:crc_t10dif_mod_fini",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_exit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/hvc/hvc_console.c:hvc_close",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/pm.c:mptcp_pm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674880,
      "name": "cancel_work_sync",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654704,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3173",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memory-failure.c:memory_failure_queue_kick",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/crc-t10dif.c:crc_t10dif_mod_fini",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_exit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/hvc/hvc_console.c:hvc_close",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/mptcp/protocol.c:mptcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654704,
      "name": "cancel_work_sync",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661152,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3174",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memory-failure.c:memory_failure_queue_kick",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/crc-t10dif.c:crc_t10dif_mod_fini",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_exit",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/hvc/hvc_console.c:hvc_close",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/mptcp/protocol.c:mptcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661152,
      "name": "cancel_work_sync",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738240,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3213",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memory-failure.c:memory_failure_queue_kick",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/crc-t10dif.c:crc_t10dif_mod_fini",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_exit",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/hvc/hvc_console.c:hvc_close",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/mptcp/protocol.c:mptcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738240,
      "name": "cancel_work_sync",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579841632,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3196",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memory-failure.c:memory_failure_queue_kick",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/crc-t10dif.c:crc_t10dif_mod_fini",
        "lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/hvc/hvc_console.c:hvc_close",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/mptcp/protocol.c:mptcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579841632,
      "name": "cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579978464,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3194",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memory-failure.c:memory_failure_queue_kick",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/crc-t10dif.c:crc_t10dif_mod_fini",
        "lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/hvc/hvc_console.c:hvc_close",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_map_close",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_unregister",
        "net/mptcp/protocol.c:mptcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978464,
      "name": "cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580028064,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3510",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:put_unbound_pool"
      ],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memory-failure.c:memory_failure_queue_kick",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/crc-t10dif.c:crc_t10dif_mod_fini",
        "lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/hvc/hvc_console.c:hvc_close",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release",
        "drivers/scsi/virtio_scsi.c:virtscsi_remove",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027504,
      "name": "cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580067152,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3531",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:put_unbound_pool"
      ],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memory-failure.c:memory_failure_queue_kick",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/crc-t10dif.c:crc_t10dif_mod_fini",
        "lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/pmdomain/core.c:genpd_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/hvc/hvc_console.c:hvc_close",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release",
        "drivers/scsi/virtio_scsi.c:virtscsi_remove",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_close",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066592,
      "name": "cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490809080,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3170",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_powerdown",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490809080,
      "name": "cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224845228,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3170",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224845228,
      "name": "cancel_work_sync",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283646400,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3170",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283646400,
      "name": "cancel_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271489862,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3170",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271489862,
      "name": "cancel_work_sync",
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
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579619520,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3170",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:pm_genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/nvme/host/core.c:nvme_stop_ctrl",
        "drivers/nvme/host/multipath.c:nvme_mpath_stop",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619520,
      "name": "cancel_work_sync",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547888,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3170",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:pm_genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete",
        "drivers/nvme/host/core.c:nvme_stop_ctrl",
        "drivers/nvme/host/multipath.c:nvme_mpath_stop",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547888,
      "name": "cancel_work_sync",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579616800,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3170",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:pm_genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/scsi/virtio_scsi.c:virtscsi_remove",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616800,
      "name": "cancel_work_sync",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct * work)
```

```json
{
  "name": "cancel_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579648560,
      "name": "cancel_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3170",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "crypto/drbg.c:drbg_uninstantiate",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:blk_throtl_exit",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/tty_buffer.c:tty_buffer_cancel_work",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/domain.c:pm_genpd_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/input/serio/serio.c:serio_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/power/supply/charger-manager.c:charger_extcon_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648560,
      "name": "cancel_work_sync",
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
