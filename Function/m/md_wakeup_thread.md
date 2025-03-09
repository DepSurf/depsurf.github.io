# Function: <code>md_wakeup_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585717376,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7121",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_unplug",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/bitmap.c:timeout_store",
        "drivers/md/bitmap.c:write_page",
        "drivers/md/bitmap.c:bitmap_load",
        "drivers/md/bitmap.c:location_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717376,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586116064,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7161",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:md_unplug",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/bitmap.c:timeout_store",
        "drivers/md/bitmap.c:bitmap_load",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586116064,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586317760,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7218",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:md_unplug",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/bitmap.c:timeout_store",
        "drivers/md/bitmap.c:bitmap_load",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586317760,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586426224,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7439",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/bitmap.c:timeout_store",
        "drivers/md/bitmap.c:bitmap_load",
        "drivers/md/bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586426224,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586881552,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7494",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586881552,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587181792,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7563",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587181792,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587361984,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7550",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361984,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587627344,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7612",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587627344,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587831168,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7716",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587831168,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588687552,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7914",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588687552,
      "name": "md_wakeup_thread",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588714336,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7942",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588714336,
      "name": "md_wakeup_thread",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588599392,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7896",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588599392,
      "name": "md_wakeup_thread",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589276272,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7909",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589276272,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590737104,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7906",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590737104,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592413648,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7896",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592413648,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592842736,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7904",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592842736,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593591904,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:8036",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:__mddev_resume",
        "drivers/md/md.c:__mddev_resume",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_sb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593591904,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501068456,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7716",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501068456,
      "name": "md_wakeup_thread",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233567892,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7716",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233567892,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294537456,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7716",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294537456,
      "name": "md_wakeup_thread",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277782748,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7716",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277782748,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587462144,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7716",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587462144,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587230320,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7716",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587230320,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587787312,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7716",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587787312,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void md_wakeup_thread(struct md_thread * thread)
```

```json
{
  "name": "md_wakeup_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587902560,
      "name": "md_wakeup_thread",
      "external": true,
      "loc": "drivers/md/md.c:7716",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_safemode_timeout",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md-bitmap.c:timeout_store",
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587902560,
      "name": "md_wakeup_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
