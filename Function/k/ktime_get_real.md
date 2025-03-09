# Function: <code>ktime_get_real</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579822880,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579872496,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580391457,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584169345,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585349937,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585583640,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586172440,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586204366,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_get_timestamp",
        "net/core/sock.c:sock_get_timestampns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586213936,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586255431,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_tcpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_tcp_sequence_number"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586289146,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:dev_hard_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586440305,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestampns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586892113,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586979124,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587181266,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:177",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822880,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579872496,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851520,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579901920,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580459201,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583495766,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584506049,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585750857,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585977672,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586593576,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586625406,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586639456,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586680200,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586722009,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586886188,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587338816,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587425613,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587635657,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851520,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579901920,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579880128,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579912192,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580521649,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583635910,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584688161,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585939497,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586165992,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586777940,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586809934,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586825028,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586864840,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586908537,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587080268,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587541760,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587629005,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587840041,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880128,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579912192,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579889440,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579921344,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580554241,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583675894,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584770739,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586023401,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586254688,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586898410,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586931680,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586959335,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586987632,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587040162,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587208576,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587687813,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587778376,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587997521,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:182",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889440,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579921344,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579933952,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579966576,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580635009,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583933590,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585190835,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586467609,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586718176,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587390138,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587424672,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587451543,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587485980,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587540478,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587722896,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588214549,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588306572,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588534065,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933952,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579966576,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579981856,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580014176,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580761568,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584118149,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585424477,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586731595,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586983679,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587691418,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587728926,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587755273,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587791166,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587832080,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588056460,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_sock_get_timestampns",
        "net/compat.c:compat_sock_get_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588569204,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588662184,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588898399,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:62",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981856,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071580014176,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580028656,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580061200,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580828384,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584201477,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585550509,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586900923,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587144799,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587825527,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587862468,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_get_timestampns",
        "net/core/sock.c:sock_get_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587889881,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587925262,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587987711,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588232866,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588766228,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588879328,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589121900,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028656,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071580061200,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071536,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580104800,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580923344,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584390325,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605034470,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587158553,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587409759,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588128256,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588167112,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588195566,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588234158,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588299632,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589199256,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589318199,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589575208,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071536,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071580104800,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580121072,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580153776,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580977536,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584525909,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605071081,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587358953,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588333392,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588372392,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588400734,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588438878,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588500613,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588759269,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588796362,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589424520,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589542599,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589799592,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121072,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071580153776,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580181024,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580214016,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580219077,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_realtime_ktime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144064,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609359026,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588206553,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589196261,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589238008,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589261756,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589307194,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589372304,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589632245,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589674706,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590546784,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590822791,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181024,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071580214016,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580165952,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580198288,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580203333,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_realtime_ktime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581184112,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585380550,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612430262,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588243604,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589194629,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237672,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589260892,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589306154,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589377845,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589654725,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589706322,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590604753,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590882807,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:76",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165952,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071580198288,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580170512,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580203600,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580208629,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_realtime_ktime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581202480,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585265574,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614571282,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:rand_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588127785,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589088069,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589131464,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589164316,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589200110,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589279208,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589544021,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589587833,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590529970,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590811536,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170512,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071580203600,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580314880,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580350304,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580356149,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_realtime_ktime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442128,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583664499,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585721651,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615526182,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:rand_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588765404,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589806030,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589846904,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589879132,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589922043,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590006591,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590288213,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590332507,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591336948,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591629242,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591662232,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314880,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071580350304,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580525776,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580564624,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580570821,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_realtime_ktime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581783376,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584233251,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586892417,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588497447,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590189660,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591324763,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591354625,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591403449,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591453620,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591540794,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591871413,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591919375,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_health_do_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592302621,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593010800,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593055692,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593321797,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593357179,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593485639,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525776,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580564624,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580781616,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580824816,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580831413,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_realtime_ktime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582209152,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584876803,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588039584,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:line_event_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589937607,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591806203,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593081798,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593110750,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593168519,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593221364,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593314282,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593672117,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593724303,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_health_do_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594138749,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594900427,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594948268,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595226773,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595264310,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595403978,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781616,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580824816,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580864608,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580908320,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580914965,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_realtime_ktime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409168,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585104026,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588314224,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:line_event_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590246887,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592229755,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593531238,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593563230,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593631649,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593681604,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593775946,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594152693,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594525885,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595291758,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595340924,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595622916,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595659974,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595800564,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595912543,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/devlink/health.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_health_do_dump"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864608,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580908320,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580955280,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580998848,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581005573,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_realtime_ktime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582577392,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585336394,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607121,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:line_event_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590587911,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592970856,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594303763,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594335822,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594407290,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594459732,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594556394,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594949045,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595328573,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_local_deliver_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596132890,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596181644,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_input_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596470164,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596507750,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data",
        "net/ipv6/ioam6.c:__ioam6_fill_trace_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596651197,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596745825,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "net/devlink/health.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_health_do_dump"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955280,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580998848,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491338512,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491371808,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492326272,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496703296,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511216964,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500038928,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/net/ethernet/freescale/fec_ptp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500470384,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501827112,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501882720,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501917004,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501962164,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502032156,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502327396,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502367104,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503078652,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503212612,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503504820,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491338512,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336491371808,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224528864,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "arch/arm/common/bL_switcher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/common/bL_switcher.c:bL_switcher_trace_trigger_cpu",
        "arch/arm/common/bL_switcher.c:bL_switch_to",
        "arch/arm/common/bL_switcher.c:bL_switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 3225331968,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225373868,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226218324,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 3230000460,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 3243860136,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3232558240,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/net/ethernet/freescale/fec_ptp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter"
      ],
      "caller_func": []
    },
    {
      "addr": 3232567064,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/net/ethernet/ti/cpts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpts.c:cpts_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3232939244,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 3234612860,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 3234646528,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 3234677276,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 3234715960,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 3234784380,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 3235063472,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 3235103880,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235760396,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235884284,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3236157700,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225331968,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3225373868,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284268880,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284313520,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285572596,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290795696,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302775632,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293831296,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295228832,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295290512,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295332572,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295386652,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295476428,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295838916,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295904576,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296782636,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296949324,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297296448,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284268880,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 13835058055284313520,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271836220,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271863954,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272451138,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275469914,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270793040,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277370796,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278173484,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278203022,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278229066,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278263120,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278321490,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278547460,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278583268,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279133362,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279249852,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279477554,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271836220,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446743936271863954,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580090272,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580122976,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580946336,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584482837,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604970704,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586478600,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_init_identify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587065033,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587940176,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587979176,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588007518,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045662,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588107353,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588366005,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402746,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589028888,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589146967,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589403960,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090272,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071580122976,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580035600,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580068272,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580892400,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584420965,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604935005,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586354776,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_init_identify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587653280,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587692280,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587720606,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587758750,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820233,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588078709,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588115434,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588753928,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588871959,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589128952,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035600,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071580068272,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580081344,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580114048,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580937584,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584477573,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605051404,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587313513,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588271952,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588310952,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588339294,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588377438,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588439173,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588697829,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588734922,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588937905,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/netfilter/nf_conntrack_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588942136,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/netfilter/nf_conntrack_standalone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_standalone.c:ct_seq_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588995277,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/netfilter/nf_conntrack_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589465752,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589583831,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589840824,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081344,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071580114048,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_real()
```

```json
{
  "name": "ktime_get_real",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580132880,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580165840,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580999168,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_real_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584583685,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605075275,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587423753,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588407232,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sock_recv_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588446168,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_gettstamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588474766,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_tstamp_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588513134,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588575791,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_receive_skb_list_internal",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:dev_queue_xmit_nit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588837669,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588875386,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589631632,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589892104,
      "name": "ktime_get_real",
      "external": false,
      "loc": "include/linux/timekeeping.h:77",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_dest_hao"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132880,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071580165840,
      "name": "ktime_get_real",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
