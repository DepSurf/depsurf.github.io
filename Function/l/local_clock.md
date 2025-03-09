# Function: <code>local_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579571312,
      "name": "local_clock",
      "external": true,
      "loc": "kernel/sched/clock.c:386",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/printk/printk.c:log_store",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:perf_event_update_userpage",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "net/core/datagram.c:__skb_recv_datagram",
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_send_ack",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_recovery.c:tcp_rack_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571312,
      "name": "local_clock",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578853941,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579582385,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579669459,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579745353,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580189713,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580453880,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245035,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586304629,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586722906,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:sk_busy_loop",
        "net/core/dev.c:sk_busy_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587086372,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587124072,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_send_ack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134159,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587169843,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2473",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_advance"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580453840,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578853977,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579608561,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579621008,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579694067,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579773961,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580230337,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580516312,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581322793,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586512469,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586901282,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:sk_busy_loop",
        "net/core/dev.c:sk_busy_loop",
        "net/core/dev.c:sk_busy_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587283202,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587321848,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_send_ack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_transmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587332760,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587369891,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched.h:2569",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_advance"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580516272,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578854025,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579586161,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579596212,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579690083,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579770095,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580240033,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580547848,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375398,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588710,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586638096,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586918655,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587026429,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587378545,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587414756,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_init_buffer_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587460006,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587464727,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587482965,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587684429,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587990654,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:81",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580547808,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578854059,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579615585,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579626179,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579721027,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803194,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580291265,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580628216,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516870,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732566,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587119442,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587410911,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587523885,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587899811,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587934581,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust",
        "net/ipv4/tcp_input.c:tcp_init_buffer_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587981910,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587982758,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588004983,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588211165,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588526912,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628016,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578853397,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579645936,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659354,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579754070,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579836563,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:log_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580352528,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580757088,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674558,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900293,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587419074,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589272319,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587714289,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587824541,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588249679,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588283852,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust",
        "net/ipv4/tcp_input.c:tcp_init_buffer_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588332181,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588333094,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588355686,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588565733,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588892066,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756880,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578853397,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579683504,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693483,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579796950,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579883645,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:log_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604730042,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408768,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580823408,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581760851,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581985166,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587599267,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589515317,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587847617,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587957837,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823200,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578853557,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717280,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579825094,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579919042,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:cont_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604831307,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580461728,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551584,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580918080,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581878522,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582120789,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587876071,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587884304,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589974470,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588152017,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588272621,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917872,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578853557,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579759712,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579873798,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579969106,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:cont_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580056716,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604865577,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580510608,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580599248,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580971536,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581950729,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198021,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588081671,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588090193,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590201806,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588357252,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588501341,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580971328,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857701,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793328,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579915830,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580016245,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:cont_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580116170,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609194862,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580597440,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580699508,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140736,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_event_account_interrupt",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582179525,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582436328,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588943852,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588952529,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591217600,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589217031,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589372957,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140528,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857911,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784176,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579909366,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003678,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580098010,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612261368,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580587392,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580690292,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581180768,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_event_account_interrupt",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582226749,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582492312,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588915282,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588956257,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588964785,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591712032,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589215111,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589381958,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581180560,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857911,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792288,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917926,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580005118,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580102226,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614402338,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580590384,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580694500,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581199248,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_event_account_interrupt",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252755,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582520080,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588803746,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588844673,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588852929,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591659424,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589108754,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589276198,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581199040,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857975,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888048,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580044026,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580136943,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580242090,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615337686,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580752108,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_thrashing_end",
        "kernel/delayacct.c:__delayacct_thrashing_start",
        "kernel/delayacct.c:__delayacct_freepages_end",
        "kernel/delayacct.c:__delayacct_freepages_start",
        "kernel/delayacct.c:__delayacct_blkio_end",
        "kernel/delayacct.c:__delayacct_blkio_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580761248,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871060,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439392,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_event_account_interrupt",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582235543,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:metadata_update_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570665,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582836048,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589496306,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589542205,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589554276,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592833152,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589826738,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590004982,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439360,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580176104,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580280893,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580402913,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617122464,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580967196,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_wpcopy_end",
        "kernel/delayacct.c:__delayacct_wpcopy_start",
        "kernel/delayacct.c:__delayacct_compact_end",
        "kernel/delayacct.c:__delayacct_compact_start",
        "kernel/delayacct.c:__delayacct_swapin_end",
        "kernel/delayacct.c:__delayacct_swapin_start",
        "kernel/delayacct.c:__delayacct_thrashing_end",
        "kernel/delayacct.c:__delayacct_thrashing_start",
        "kernel/delayacct.c:__delayacct_freepages_end",
        "kernel/delayacct.c:__delayacct_freepages_start",
        "kernel/delayacct.c:__delayacct_blkio_end",
        "kernel/delayacct.c:__delayacct_blkio_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977152,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101423,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581779525,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_event_account_interrupt",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582704771,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:metadata_update_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583099984,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583397357,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590978818,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591034989,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591047934,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594744409,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591349678,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591542878,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779488,
      "name": "local_clock",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580358824,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580489610,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580630275,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627792050,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581262828,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_wpcopy_end",
        "kernel/delayacct.c:__delayacct_wpcopy_start",
        "kernel/delayacct.c:__delayacct_compact_end",
        "kernel/delayacct.c:__delayacct_compact_start",
        "kernel/delayacct.c:__delayacct_swapin_end",
        "kernel/delayacct.c:__delayacct_swapin_start",
        "kernel/delayacct.c:__delayacct_thrashing_end",
        "kernel/delayacct.c:__delayacct_thrashing_start",
        "kernel/delayacct.c:__delayacct_freepages_end",
        "kernel/delayacct.c:__delayacct_freepages_start",
        "kernel/delayacct.c:__delayacct_blkio_end",
        "kernel/delayacct.c:__delayacct_blkio_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581273328,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409319,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205077,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_event_account_interrupt",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583230707,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:metadata_update_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583668050,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583983757,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592684050,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592745888,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592759934,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596497083,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593104174,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593316414,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205024,
      "name": "local_clock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580429480,
      "name": "local_clock",
      "external": true,
      "loc": "kernel/sched/clock.c:311",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:running_clock"
      ],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/timekeeping.c:dummy_clock_read",
        "kernel/delayacct.c:__delayacct_wpcopy_end",
        "kernel/delayacct.c:__delayacct_wpcopy_start",
        "kernel/delayacct.c:__delayacct_compact_end",
        "kernel/delayacct.c:__delayacct_compact_start",
        "kernel/delayacct.c:__delayacct_swapin_end",
        "kernel/delayacct.c:__delayacct_swapin_start",
        "kernel/delayacct.c:__delayacct_thrashing_end",
        "kernel/delayacct.c:__delayacct_thrashing_start",
        "kernel/delayacct.c:__delayacct_freepages_end",
        "kernel/delayacct.c:__delayacct_freepages_start",
        "kernel/delayacct.c:__delayacct_blkio_end",
        "kernel/delayacct.c:__delayacct_blkio_start",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_event_account_interrupt",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "mm/kfence/core.c:metadata_update_state",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580429360,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580489032,
      "name": "local_clock",
      "external": true,
      "loc": "kernel/sched/clock.c:311",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:running_clock"
      ],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/time/timekeeping.c:dummy_clock_read",
        "kernel/delayacct.c:__delayacct_wpcopy_end",
        "kernel/delayacct.c:__delayacct_wpcopy_start",
        "kernel/delayacct.c:__delayacct_compact_end",
        "kernel/delayacct.c:__delayacct_compact_start",
        "kernel/delayacct.c:__delayacct_swapin_end",
        "kernel/delayacct.c:__delayacct_swapin_start",
        "kernel/delayacct.c:__delayacct_thrashing_end",
        "kernel/delayacct.c:__delayacct_thrashing_start",
        "kernel/delayacct.c:__delayacct_freepages_end",
        "kernel/delayacct.c:__delayacct_freepages_start",
        "kernel/delayacct.c:__delayacct_blkio_end",
        "kernel/delayacct.c:__delayacct_blkio_start",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:__perf_event_account_interrupt",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "mm/kfence/core.c:metadata_update_state",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_reset_table",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580488912,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490174108,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490937608,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491077260,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491149308,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:cont_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491267028,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510900604,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491790152,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491897800,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492335440,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_update",
        "kernel/events/core.c:__perf_event_account_interrupt",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493446592,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493760876,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501325196,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501337028,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501862360,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502033192,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492322008,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224382996,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 3224955920,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 3225081188,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 3225179400,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:cont_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3225279608,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core"
      ],
      "caller_func": []
    },
    {
      "addr": 3243387252,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 3225737696,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 3225840108,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 3226207548,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:cpu_clock_event_update",
        "kernel/events/core.c:__perf_event_account_interrupt",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3227016544,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 3227279800,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 3233815536,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 3233826492,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 3234078400,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "drivers/firmware/tegra/bpmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic",
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 3234629228,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 3234785296,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226207320,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282226016,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282343552,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "arch/powerpc/kernel/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/time.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283793556,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283957868,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284048044,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:cont_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284176280,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302535884,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284839668,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284984004,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285564920,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_update",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287001672,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287373040,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294869164,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294883984,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295269016,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295477936,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285562416,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271334710,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271570188,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271664544,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271706754,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271789658,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270638832,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272104178,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272186122,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272447362,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:__perf_event_account_interrupt",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273134580,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273362826,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278189318,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278322240,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:48",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272447202,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578853557,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579735632,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579845942,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579937842,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:cont_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580025452,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604771034,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580479408,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580568048,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940336,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581919465,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582166757,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587703495,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587711777,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589804094,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587964036,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588108077,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940128,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578846629,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664432,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579780873,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579876322,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:cont_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579960710,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604739627,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580426544,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580514720,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580886400,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857049,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582104197,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587481767,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587490273,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589526456,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587677140,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820957,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886192,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578853557,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579720080,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579834166,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579929378,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:cont_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580016988,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604848221,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580470656,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559296,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580931584,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581910777,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582157237,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588037815,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590247502,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588295812,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588439901,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931376,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
u64 local_clock()
```

```json
{
  "name": "local_clock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578853557,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767424,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:running_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579879206,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_debug_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579975362,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:cont_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580070332,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604869719,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580526816,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580616016,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_log_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992352,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581980409,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582230485,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588153399,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588162145,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590298702,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588430948,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_busy_loop_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588576605,
      "name": "local_clock",
      "external": false,
      "loc": "include/linux/sched/clock.h:82",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_busy_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992144,
      "name": "local_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
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
