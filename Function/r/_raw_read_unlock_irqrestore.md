# Function: <code>_raw_read_unlock_irqrestore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587381088,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "security/apparmor/label.c:vec_find",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "drivers/scsi/sg.c:sg_res_in_use",
        "drivers/scsi/sg.c:sg_res_in_use",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587381088,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587884048,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:vec_find",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_res_in_use",
        "drivers/scsi/sg.c:sg_res_in_use",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884048,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588102352,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:vec_find",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_res_in_use",
        "drivers/scsi/sg.c:sg_res_in_use",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588102352,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588328032,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:vec_find",
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328032,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588894208,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:254",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:vec_find",
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588894208,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589272512,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:254",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:vec_find",
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589272512,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589515648,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:254",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:vec_find",
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589515648,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589974624,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:vec_find",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589974624,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590201920,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:vec_find",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590201920,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591218240,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:labelset_next_stale",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_label_find",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591218240,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591712768,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:labelset_next_stale",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_label_find",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/leds/led-triggers.c:led_trigger_blink_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591712768,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591660224,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_label_find",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/leds/led-triggers.c:led_trigger_blink_oneshot",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591660224,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592833952,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:266",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_label_find",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/leds/led-triggers.c:led_trigger_blink_oneshot",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592833952,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594745088,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:266",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_label_find",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_broadcast",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594745088,
      "name": "_raw_read_unlock_irqrestore",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596497952,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:266",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_label_find",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_broadcast",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596497952,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597035520,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:266",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/dir.c:pr_cont_kernfs_path",
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_label_find",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_broadcast",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597035520,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597967488,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:266",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/dir.c:pr_cont_kernfs_path",
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_label_find",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597967488,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236557772,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:vec_find",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236557772,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297802432,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:vec_find",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297802432,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279811448,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:vec_find",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279811448,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589804208,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:vec_find",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589804208,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589526576,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:vec_find",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589526576,
      "name": "_raw_read_unlock_irqrestore",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590247616,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:vec_find",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590247616,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```

```json
{
  "name": "_raw_read_unlock_irqrestore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590299232,
      "name": "_raw_read_unlock_irqrestore",
      "external": true,
      "loc": "kernel/locking/spinlock.c:261",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:vec_find",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:dev_seq_start",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_poll",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_quick_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590299232,
      "name": "_raw_read_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void _raw_read_unlock_irqrestore(rwlock_t * lock, long unsigned int flags)
```
</details>
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
