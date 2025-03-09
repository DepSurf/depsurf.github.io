# Function: <code>ktime_get_real_ts64</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993680,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:713",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_gettimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993680,
      "name": "ktime_get_real_ts64",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580040304,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:720",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040304,
      "name": "ktime_get_real_ts64",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:726",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088279,
      "name": "ktime_get_real_ts64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580085088,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134176,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:726",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134176,
      "name": "ktime_get_real_ts64",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580194848,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:726",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/ntp.c:sync_cmos_clock",
        "kernel/time/posix-timers.c:posix_get_realtime_timespec",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_take_timestamp_post",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194848,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580180720,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:796",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/posix-timers.c:posix_get_realtime_timespec",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_take_timestamp_post",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180720,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580183504,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:796",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/posix-timers.c:posix_get_realtime_timespec",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_take_timestamp_post",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183504,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:796",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x64_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/posix-timers.c:posix_get_realtime_timespec",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592152699,
      "name": "ktime_get_real_ts64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580328032,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:815",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/posix-timers.c:posix_get_realtime_timespec",
        "kernel/trace/blktrace.c:trace_note_time",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593927656,
      "name": "ktime_get_real_ts64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580540064,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:815",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/posix-timers.c:posix_get_realtime_timespec",
        "kernel/trace/blktrace.c:trace_note_time",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595995737,
      "name": "ktime_get_real_ts64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580797248,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:815",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/posix-timers.c:posix_get_realtime_timespec",
        "kernel/trace/blktrace.c:trace_note_time",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_take_timestamp_post",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596514029,
      "name": "ktime_get_real_ts64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580880208,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:815",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/posix-timers.c:posix_get_realtime_timespec",
        "kernel/trace/blktrace.c:trace_note_time",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_take_timestamp_post",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597413356,
      "name": "ktime_get_real_ts64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580970640,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491347504,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:726",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__arm64_compat_sys_gettimeofday",
        "kernel/time/time.c:__arm64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491347504,
      "name": "ktime_get_real_ts64",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225340964,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:726",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__se_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/blktrace.c:__blk_trace_startstop",
        "fs/kernfs/inode.c:__kernfs_iattrs",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "sound/core/timer.c:snd_timer_user_tinterrupt",
        "sound/core/timer.c:snd_timer_notify1",
        "sound/core/pcm_native.c:snd_pcm_trigger_tstamp",
        "sound/core/pcm_native.c:snd_pcm_status",
        "sound/core/pcm_lib.c:update_audio_tstamp",
        "sound/core/pcm_lib.c:__snd_pcm_xrun",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225340964,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284278480,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:726",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__se_compat_sys_gettimeofday",
        "kernel/time/time.c:__se_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/blktrace.c:__blk_trace_startstop",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284278480,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271842052,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:726",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__se_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/blktrace.c:__blk_trace_startstop",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271842052,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580103376,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:726",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103376,
      "name": "ktime_get_real_ts64",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048688,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:726",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048688,
      "name": "ktime_get_real_ts64",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094448,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:726",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094448,
      "name": "ktime_get_real_ts64",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 * ts)
```

```json
{
  "name": "ktime_get_real_ts64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146192,
      "name": "ktime_get_real_ts64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:726",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/posix-timers.c:posix_clock_realtime_get",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "fs/kernfs/dir.c:kernfs_add_one",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ipv4/af_inet.c:inet_current_timestamp",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_open_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146192,
      "name": "ktime_get_real_ts64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void ktime_get_real_ts64(struct timespec64 * ts)
```
</details>
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
