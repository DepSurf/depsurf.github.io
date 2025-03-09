# Function: <code>flush_delayed_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480768,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:2867",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "mm/backing-dev.c:wb_shutdown",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480768,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494592,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:2967",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494592,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513264,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:2981",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:static_key_deferred_flush",
        "kernel/jump_label.c:static_key_deferred_flush",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513264,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501712,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:2980",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:static_key_deferred_flush",
        "kernel/jump_label.c:static_key_deferred_flush",
        "mm/backing-dev.c:wb_shutdown",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501712,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527728,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:2994",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:static_key_deferred_flush",
        "kernel/jump_label.c:static_key_deferred_flush",
        "mm/backing-dev.c:wb_shutdown",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527728,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555520,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3056",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:_cleanup_srcu_struct",
        "kernel/rcu/srcutree.c:_cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:static_key_deferred_flush",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555520,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593136,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3079",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:_cleanup_srcu_struct",
        "kernel/rcu/srcutree.c:_cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:static_key_deferred_flush",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593136,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618816,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3179",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618816,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642496,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3188",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642496,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673856,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3185",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "mm/backing-dev.c:wb_shutdown",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673856,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653680,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3191",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "mm/backing-dev.c:wb_shutdown",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653680,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660096,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3192",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "mm/backing-dev.c:wb_shutdown",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "fs/io_uring.c:io_ring_ctx_free",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660096,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737200,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3231",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "mm/backing-dev.c:wb_shutdown",
        "mm/backing-dev.c:wb_shutdown",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "fs/io_uring.c:io_ring_ctx_free",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737200,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579841920,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3214",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "mm/backing-dev.c:wb_shutdown",
        "mm/backing-dev.c:wb_shutdown",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_rsrc_ref_quiesce",
        "io_uring/io_uring.c:io_rsrc_ref_quiesce",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579841920,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981168,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3212",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "mm/backing-dev.c:wb_shutdown",
        "mm/backing-dev.c:wb_shutdown",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981168,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030272,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3528",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "mm/backing-dev.c:wb_shutdown",
        "mm/backing-dev.c:wb_shutdown",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "fs/quota/dquot.c:invalidate_dquots",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "io_uring/io_uring.c:io_fallback_tw",
        "io_uring/io_uring.c:io_fallback_tw",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030272,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580073104,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3549",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "mm/backing-dev.c:wb_shutdown",
        "mm/backing-dev.c:wb_shutdown",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:invalidate_dquots",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "io_uring/io_uring.c:io_fallback_tw",
        "io_uring/io_uring.c:io_fallback_tw",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_lastclose",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073104,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490810880,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3188",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490810880,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224844320,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3188",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free",
        "drivers/usb/musb/musb_core.c:musb_suspend",
        "sound/soc/soc-core.c:snd_soc_poweroff",
        "sound/soc/soc-core.c:snd_soc_suspend",
        "sound/soc/soc-pcm.c:soc_pcm_private_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224844320,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283645264,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3188",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "mm/backing-dev.c:wb_shutdown",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283645264,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271485600,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3188",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271485600,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618800,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3188",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618800,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547200,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3188",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547200,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579616080,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3188",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616080,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool flush_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "flush_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645008,
      "name": "flush_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3188",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/kprobes.c:wait_for_kprobe_optimizer",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "kernel/jump_label.c:__static_key_deferred_flush",
        "fs/notify/mark.c:fsnotify_wait_marks_destroyed",
        "drivers/base/devcoredump.c:devcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645008,
      "name": "flush_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
