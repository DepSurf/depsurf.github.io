# Function: <code>kernfs_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581511872,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:866",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/bitmap.c:bitmap_endwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581511872,
      "name": "kernfs_notify",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581697520,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:887",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/bitmap.c:bitmap_endwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697520,
      "name": "kernfs_notify",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785488,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:887",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/bitmap.c:bitmap_endwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785488,
      "name": "kernfs_notify",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840272,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:933",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/bitmap.c:bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840272,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581990016,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:933",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990016,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177664,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:933",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177664,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272816,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:921",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272816,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:931",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442085,
      "name": "kernfs_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582437264,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582535952,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:931",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535952,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582843920,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:931",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582843920,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582916576,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:913",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582916576,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582944272,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:913",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582944272,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583279424,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:913",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583279424,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583785248,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:915",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_cond_end_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583785248,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584403184,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:975",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_cond_end_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584403184,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584631744,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:975",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:update_triggers",
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/usb/core/hub.c:update_port_device_state",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_cond_end_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631744,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584863760,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:953",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:update_triggers",
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/usb/core/hub.c:update_port_device_state",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_cond_end_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863760,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494174792,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:931",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494174792,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227610272,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:931",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227610272,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287855616,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:931",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287855616,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273638938,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:931",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273638938,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504688,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:931",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504688,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441888,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:931",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/acpi/nfit/core.c:acpi_nfit_scrub",
        "drivers/acpi/nfit/core.c:__acpi_nvdimm_notify",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/pmem.c:pmem_do_bvec",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441888,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582495168,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:931",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582495168,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void kernfs_notify(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582575792,
      "name": "kernfs_notify",
      "external": true,
      "loc": "fs/kernfs/file.c:931",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:set_in_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582575792,
      "name": "kernfs_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
