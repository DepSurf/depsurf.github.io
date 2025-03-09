# Function: <code>jiffies_to_usecs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579806656,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:269",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_process_tick",
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_governor.c:dbs_check_cpu",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/ipv4/tcp_recovery.c:tcp_rack_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806656,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579834464,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:269",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_idle_ticks",
        "kernel/sched/cputime.c:account_process_tick",
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/tsacct.c:__acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_group_served",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init",
        "drivers/cpufreq/cpufreq_conservative.c:cs_init",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_update_rtt_min",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics",
        "net/ipv4/tcp_recovery.c:tcp_rack_advance",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834464,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579863520,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:269",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:account_idle_ticks",
        "kernel/sched/cputime.c:account_process_tick",
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/tsacct.c:__acct_update_integrals",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_group_served",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init",
        "drivers/cpufreq/cpufreq_conservative.c:cs_init",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics",
        "net/ipv4/tcp_rate.c:tcp_rate_gen",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_recovery.c:tcp_rack_advance",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863520,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579871744,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:359",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_group_served",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/cpufreq/cpufreq_ondemand.c:od_init",
        "drivers/cpufreq/cpufreq_conservative.c:cs_init",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871744,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579915152,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:325",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915152,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579960117,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:327",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959712,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580006693,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:325",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006368,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580050261,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:393",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049936,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580099317,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:393",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098992,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580161877,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:391",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/blk-core.c:disk_end_io_acct",
        "block/blk-core.c:disk_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/md/dm.c:dm_start_time_ns_from_clone",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161568,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580146021,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:391",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/blk-core.c:__part_end_io_acct",
        "block/blk-core.c:__part_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/md/dm.c:dm_start_time_ns_from_clone",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145712,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580150709,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:391",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/blk-core.c:__part_end_io_acct",
        "block/blk-core.c:__part_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/md/dm.c:dm_start_time_ns_from_clone",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150400,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580295237,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:391",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/blk-core.c:__part_end_io_acct",
        "block/blk-core.c:__part_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/md/dm.c:dm_start_time_ns_from_clone",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294928,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580503941,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:391",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_init",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "block/blk-core.c:bdev_end_io_acct",
        "block/blk-core.c:bdev_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/md/dm.c:dm_start_time_ns_from_clone",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580503600,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580757237,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:391",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_init",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "block/blk-core.c:bdev_end_io_acct",
        "block/blk-core.c:bdev_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/md/dm.c:dm_start_time_ns_from_clone",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756832,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580839909,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:391",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_init",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "block/blk-core.c:bdev_end_io_acct",
        "block/blk-core.c:bdev_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/net/virtio_net.c:virtnet_tx_timeout",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/md/dm.c:dm_start_time_ns_from_clone",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839504,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580929333,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:400",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_init",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "block/blk-core.c:bdev_end_io_acct",
        "block/blk-core.c:bdev_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/net/virtio_net.c:virtnet_tx_timeout",
        "drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff",
        "drivers/md/dm.c:dm_start_time_ns_from_clone",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928928,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491310392,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:393",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection",
        "drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491309912,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225306988,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:393",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "arch/arm/mach-vexpress/spc.c:spc_set_rate",
        "arch/arm/mach-vexpress/spc.c:ve_spc_populate_opps",
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init",
        "drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection",
        "drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_clk_change_notify",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225306452,
      "name": "jiffies_to_usecs",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284236248,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:393",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284235872,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271819330,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:393",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271818904,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580068517,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:393",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068192,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580013333,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:393",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013008,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580059589,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:393",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059264,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int jiffies_to_usecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_usecs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580110389,
      "name": "jiffies_to_usecs",
      "external": true,
      "loc": "kernel/time/time.c:393",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__usecs_to_jiffies"
      ],
      "caller_func": [
        "kernel/sched/psi.c:record_times",
        "kernel/sched/psi.c:psi_init",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:congestion_wait",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:timeouts_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "drivers/char/tpm/tpm-sysfs.c:durations_show",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_metrics.c:tcp_init_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110080,
      "name": "jiffies_to_usecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
