# Function: <code>sched_clock_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571088,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:294",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/clock.c:cpu_clock",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/trace/trace_clock.c:trace_clock_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571088,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579581728,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:299",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_cpu_starting",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/printk/printk.c:log_store",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
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
        "kernel/events/core.c:ctx_sched_out",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/dev.c:sk_busy_loop",
        "net/core/dev.c:sk_busy_loop",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_send_ack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_recovery.c:tcp_rack_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581728,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607904,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:299",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_cpu_starting",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/printk/printk.c:log_store",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
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
        "kernel/events/core.c:ctx_sched_out",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/dev.c:sk_busy_loop",
        "net/core/dev.c:sk_busy_loop",
        "net/core/dev.c:sk_busy_loop",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_send_ack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_recovery.c:tcp_rack_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607904,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579585616,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:357",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_cpu_starting",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/printk/printk.c:log_store",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
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
        "kernel/events/core.c:ctx_sched_out",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_init_buffer_space",
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/syncookies.c:cookie_init_timestamp",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585616,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579615056,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:357",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_cpu_starting",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/printk/printk.c:log_store",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust",
        "net/ipv4/tcp_input.c:tcp_init_buffer_space",
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/syncookies.c:cookie_init_timestamp",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615056,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579645392,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:345",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_cpu_starting",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/printk/printk.c:log_store",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust",
        "net/ipv4/tcp_input.c:tcp_init_buffer_space",
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/syncookies.c:cookie_init_timestamp",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645392,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579683008,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:364",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:update_rq_clock",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:update_stats",
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:log_store",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683008,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579716816,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:365",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:update_rq_clock",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:collect_percpu_times",
        "kernel/printk/printk.c:cont_add",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716816,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579759248,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:365",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:collect_percpu_times",
        "kernel/printk/printk.c:cont_add",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759248,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579792752,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:365",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:update_rq_clock",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:record_times",
        "kernel/printk/printk.c:cont_add",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792752,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579783600,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:365",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:update_rq_clock",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:record_times",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
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
        "kernel/events/core.c:__perf_remove_from_context",
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
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783600,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791712,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:365",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:update_rq_clock",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:collect_percpu_times",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791712,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887456,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:365",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:update_rq_clock",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:collect_percpu_times",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/delayacct.c:__delayacct_thrashing_end",
        "kernel/delayacct.c:__delayacct_thrashing_start",
        "kernel/delayacct.c:__delayacct_freepages_end",
        "kernel/delayacct.c:__delayacct_freepages_start",
        "kernel/delayacct.c:__delayacct_blkio_end",
        "kernel/delayacct.c:__delayacct_blkio_start",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "mm/kfence/core.c:metadata_update_state",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887456,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580169616,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:363",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:update_rq_clock",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change",
        "kernel/sched/build_utility.c:collect_percpu_times",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:running_clock",
        "kernel/sched/build_utility.c:sched_clock_idle_sleep_event",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
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
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "mm/kfence/core.c:metadata_update_state",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169616,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580347632,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:363",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:update_rq_clock",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/build_utility.c:psi_cgroup_restart",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change",
        "kernel/sched/build_utility.c:get_recent_times",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:running_clock",
        "kernel/sched/build_utility.c:sched_clock_idle_sleep_event",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
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
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
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
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580347632,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580418944,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:388",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:update_rq_clock",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/build_utility.c:psi_cgroup_restart",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change",
        "kernel/sched/build_utility.c:get_recent_times",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:sched_clock_idle_sleep_event",
        "kernel/trace/trace_clock.c:trace_clock_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580418944,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580475600,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:388",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:update_rq_clock",
        "kernel/sched/fair.c:switched_from_fair",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:rq_offline_fair",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/build_utility.c:psi_cgroup_restart",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change",
        "kernel/sched/build_utility.c:get_recent_times",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:proc_sched_show_task",
        "kernel/sched/build_utility.c:sched_clock_idle_sleep_event",
        "kernel/trace/trace_clock.c:trace_clock_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475600,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490937576,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:461",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/trace/trace_clock.c:trace_clock_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490937576,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224955856,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:461",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/trace/trace_clock.c:trace_clock_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224955856,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283793456,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:461",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/trace/trace_clock.c:trace_clock_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283793456,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271570148,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:461",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/trace/trace_clock.c:trace_clock_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271570148,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579735168,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:365",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:collect_percpu_times",
        "kernel/printk/printk.c:cont_add",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735168,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579663968,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:365",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:collect_percpu_times",
        "kernel/printk/printk.c:cont_add",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663968,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579719616,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:365",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:collect_percpu_times",
        "kernel/printk/printk.c:cont_add",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719616,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
u64 sched_clock_cpu(int cpu)
```

```json
{
  "name": "sched_clock_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579766928,
      "name": "sched_clock_cpu",
      "external": true,
      "loc": "kernel/sched/clock.c:365",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_idle_sleep_event",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:collect_percpu_times",
        "kernel/printk/printk.c:cont_add",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace.c:tracing_log_err",
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
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "drivers/cpuidle/poll_state.c:poll_idle",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/dev.c:napi_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579766928,
      "name": "sched_clock_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
