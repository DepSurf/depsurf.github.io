# Function: <code>mddev_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585717600,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:592",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717600,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586116288,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:587",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586116288,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586317984,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:600",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586317984,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586426400,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:612",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586426400,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586881712,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:646",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586881712,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587195488,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:657",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587195488,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587375584,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:650",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587375584,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587647376,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:711",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647376,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587851472,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:723",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587851472,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588692736,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:849",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588692736,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588720064,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:831",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_set_read_only",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588720064,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588610128,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:790",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_set_read_only",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588610128,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589287168,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:791",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_set_read_only",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589287168,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590742496,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:796",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_set_read_only",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:bitmap_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590742496,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592413888,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:785",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_set_read_only",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:bitmap_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592413888,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592894080,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:753",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_set_read_only",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:bitmap_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592894080,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593645216,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:864",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_set_read_only",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:stop_sync_thread",
        "drivers/md/md.c:stop_sync_thread",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:metadata_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:bitmap_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593645216,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501083368,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:723",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501083368,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233573432,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:723",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233573432,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294542320,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:723",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294542320,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277803922,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:723",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277803922,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587482448,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:723",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587482448,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587250608,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:723",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587250608,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587807616,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:723",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807616,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void mddev_unlock(struct mddev * mddev)
```

```json
{
  "name": "mddev_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587905808,
      "name": "mddev_unlock",
      "external": true,
      "loc": "drivers/md/md.c:723",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_stop_writes",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_direction_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:reshape_position_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:size_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:resync_start_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:chunk_size_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587905808,
      "name": "mddev_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
