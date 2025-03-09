# Function: <code>nsecs_to_jiffies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579807552,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:742",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:cputime_adjust",
        "kernel/sched/cputime.c:account_process_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807552,
      "name": "nsecs_to_jiffies",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835408,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:749",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:cputime_adjust",
        "kernel/sched/cputime.c:account_idle_ticks",
        "kernel/sched/cputime.c:account_process_tick",
        "block/cfq-iosched.c:cfq_completed_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835408,
      "name": "nsecs_to_jiffies",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864464,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:749",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:cputime_adjust",
        "kernel/sched/cputime.c:account_idle_ticks",
        "kernel/sched/cputime.c:account_process_tick",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/blk-wbt.c:rwb_arm_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864464,
      "name": "nsecs_to_jiffies",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872720,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:849",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_completed_request",
        "block/blk-wbt.c:rwb_arm_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872720,
      "name": "nsecs_to_jiffies",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916128,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:816",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_completed_request",
        "block/blk-wbt.c:rwb_arm_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916128,
      "name": "nsecs_to_jiffies",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579960768,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:828",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:rwb_arm_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960768,
      "name": "nsecs_to_jiffies",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007344,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:766",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:update_stats",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007344,
      "name": "nsecs_to_jiffies",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050928,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:844",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050928,
      "name": "nsecs_to_jiffies",
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099984,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:844",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099984,
      "name": "nsecs_to_jiffies",
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:754",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164048,
      "name": "nsecs_to_jiffies",
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:754",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack_probe",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148192,
      "name": "nsecs_to_jiffies",
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:754",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152880,
      "name": "nsecs_to_jiffies",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:754",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "fs/ext4/super.c:ext4_run_li_request",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297408,
      "name": "nsecs_to_jiffies",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:754",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_avgs_work",
        "kernel/sched/build_utility.c:collect_percpu_times",
        "fs/ext4/super.c:ext4_run_li_request",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505984,
      "name": "nsecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:754",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_avgs_work",
        "kernel/sched/build_utility.c:collect_percpu_times",
        "fs/ext4/super.c:ext4_run_li_request",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer",
        "drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout",
        "drivers/tty/serial/8250/8250_core.c:serial8250_timeout",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759616,
      "name": "nsecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:754",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_rtpoll_work",
        "kernel/sched/build_utility.c:psi_avgs_work",
        "kernel/sched/build_utility.c:collect_percpu_times",
        "fs/ext4/super.c:ext4_run_li_request",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer",
        "drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout",
        "drivers/tty/serial/8250/8250_core.c:serial8250_timeout",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842288,
      "name": "nsecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:829",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_rtpoll_work",
        "kernel/sched/build_utility.c:psi_avgs_work",
        "kernel/sched/build_utility.c:collect_percpu_times",
        "fs/ext4/super.c:ext4_run_li_request",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer",
        "drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout",
        "drivers/tty/serial/8250/8250_core.c:serial8250_timeout",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931680,
      "name": "nsecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491311352,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:844",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491311352,
      "name": "nsecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225309952,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:844",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/mmc/host/sdhci.c:sdhci_send_command",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225309952,
      "name": "nsecs_to_jiffies",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284237088,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:844",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284237088,
      "name": "nsecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271820070,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:844",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271820070,
      "name": "nsecs_to_jiffies",
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580069184,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:844",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069184,
      "name": "nsecs_to_jiffies",
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014000,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:844",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014000,
      "name": "nsecs_to_jiffies",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580060256,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:844",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060256,
      "name": "nsecs_to_jiffies",
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
long unsigned int nsecs_to_jiffies(u64 n)
```

```json
{
  "name": "nsecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111024,
      "name": "nsecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:844",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "block/blk-wbt.c:rwb_arm_timer",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111024,
      "name": "nsecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
