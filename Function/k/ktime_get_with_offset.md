# Function: <code>ktime_get_with_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850768,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:725",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/sys.c:do_sysinfo",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/events/core.c:ktime_get_tai_ns",
        "kernel/events/core.c:ktime_get_boot_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/compat.c:compat_sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestampns",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850768,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579879712,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:730",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/events/core.c:ktime_get_tai_ns",
        "kernel/events/core.c:ktime_get_boot_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestamp",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879712,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891776,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:759",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/events/core.c:ktime_get_tai_ns",
        "kernel/events/core.c:ktime_get_boot_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestamp",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891776,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579901040,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:791",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/events/core.c:ktime_get_tai_ns",
        "kernel/events/core.c:ktime_get_boot_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestamp",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901040,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579945840,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:795",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_tai_ns",
        "kernel/events/core.c:ktime_get_boot_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestamp",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945840,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993488,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:777",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_tai_ns",
        "kernel/events/core.c:ktime_get_boot_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestamp",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993488,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580040112,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:784",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_tai_ns",
        "kernel/events/core.c:ktime_get_boot_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040112,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:790",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088260,
      "name": "ktime_get_with_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580084912,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133984,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:790",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133984,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580194656,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:790",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_realtime_ktime",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194656,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580180528,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:860",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_realtime_ktime",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180528,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580183312,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:860",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_realtime_ktime",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/char/random.c:rand_initialize",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183312,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:860",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_realtime_ktime",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request",
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/char/random.c:rand_initialize",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592152438,
      "name": "ktime_get_with_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580326752,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:879",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_realtime_ktime",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request",
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/devlink.c:devlink_health_do_dump",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593927389,
      "name": "ktime_get_with_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580538720,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:879",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_realtime_ktime",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request",
        "drivers/gpio/gpiolib-cdev.c:line_event_timestamp",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/devlink.c:devlink_health_do_dump",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595995470,
      "name": "ktime_get_with_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580795856,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:879",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_realtime_ktime",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request",
        "drivers/gpio/gpiolib-cdev.c:line_event_timestamp",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/devlink/health.c:devlink_health_do_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596513762,
      "name": "ktime_get_with_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580878816,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:879",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_realtime_ktime",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request",
        "drivers/gpio/gpiolib-cdev.c:line_event_timestamp",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/exthdrs.c:ipv6_dest_hao",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/devlink/health.c:devlink_health_do_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597413089,
      "name": "ktime_get_with_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580969248,
      "name": "ktime_get_with_offset",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491347760,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:790",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491347760,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225341392,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:790",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/common/bL_switcher.c:bL_switcher_trace_trigger_cpu",
        "arch/arm/common/bL_switcher.c:bL_switch_to",
        "arch/arm/common/bL_switcher.c:bL_switch_to",
        "kernel/fork.c:copy_process",
        "kernel/sys.c:__se_sys_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter",
        "drivers/net/ethernet/ti/cpts.c:cpts_register",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225341392,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284279120,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:790",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284279120,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271842240,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:790",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/sys.c:__do_sys_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271842240,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580103184,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:790",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/nvme/host/core.c:nvme_init_identify",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103184,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048496,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:790",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/nvme/host/core.c:nvme_init_identify",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048496,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094256,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:790",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm",
        "net/netfilter/nf_conntrack_standalone.c:ct_seq_start",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094256,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
ktime_t ktime_get_with_offset(enum tk_offsets offs)
```

```json
{
  "name": "ktime_get_with_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146000,
      "name": "ktime_get_with_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:790",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/sys.c:do_sysinfo",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/hrtimer.c:ktime_get_clocktai",
        "kernel/time/hrtimer.c:ktime_get_boottime",
        "kernel/time/hrtimer.c:ktime_get_real",
        "kernel/time/alarmtimer.c:ktime_get_boottime",
        "kernel/time/alarmtimer.c:ktime_get_real",
        "kernel/time/posix-timers.c:posix_get_tai",
        "kernel/time/posix-timers.c:posix_get_boottime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:ktime_get_clocktai_ns",
        "kernel/events/core.c:ktime_get_boottime_ns",
        "kernel/events/core.c:ktime_get_real_ns",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/char/random.c:init_std_data",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_gettstamp",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146000,
      "name": "ktime_get_with_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
