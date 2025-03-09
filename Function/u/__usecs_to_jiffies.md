# Function: <code>__usecs_to_jiffies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579806976,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:523",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer",
        "drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate",
        "drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_timer",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806976,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579834784,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:530",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834784,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579863840,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:530",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863840,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872064,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:620",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872064,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915472,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:587",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915472,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579960112,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:599",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960112,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006688,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:537",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006688,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050256,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:605",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050256,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099312,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:605",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099312,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580161872,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:563",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_start_period",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/ipv4/tcp_cubic.c:bictcp_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161872,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146016,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:563",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_start_period",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/ipv4/tcp_cubic.c:bictcp_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146016,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150704,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:563",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_start_period",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/ipv4/tcp_cubic.c:bictcp_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150704,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580295232,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:563",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_start_period",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/ipv4/tcp_cubic.c:bictcp_update",
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295232,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580503936,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:563",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_start_period",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/core/filter.c:_bpf_setsockopt",
        "net/core/filter.c:_bpf_setsockopt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/ipv4/tcp_cubic.c:bictcp_update",
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580503936,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757232,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:563",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_start_period",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/core/filter.c:sol_tcp_sockopt",
        "net/core/filter.c:sol_tcp_sockopt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/ipv4/tcp_cubic.c:bictcp_update",
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757232,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580839904,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:563",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_start_period",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/core/filter.c:sol_tcp_sockopt",
        "net/core/filter.c:sol_tcp_sockopt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/ipv4/tcp_cubic.c:bictcp_update",
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839904,
      "name": "__usecs_to_jiffies",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929328,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:588",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_start_period",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/core/filter.c:sol_tcp_sockopt",
        "net/core/filter.c:sol_tcp_sockopt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/ipv4/tcp_cubic.c:bictcp_update",
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929328,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491310368,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:605",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491310368,
      "name": "__usecs_to_jiffies",
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225306968,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:605",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "block/blk-iocost.c:ioc_start_period",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe",
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer",
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225306968,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284236240,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:605",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284236240,
      "name": "__usecs_to_jiffies",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271819308,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:605",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271819308,
      "name": "__usecs_to_jiffies",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580068512,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:605",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068512,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013328,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:605",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013328,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580059584,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:605",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059584,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int __usecs_to_jiffies(const unsigned int u)
```

```json
{
  "name": "__usecs_to_jiffies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110384,
      "name": "__usecs_to_jiffies",
      "external": true,
      "loc": "kernel/time/time.c:605",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "net/core/dev.c:net_rx_action",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110384,
      "name": "__usecs_to_jiffies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
