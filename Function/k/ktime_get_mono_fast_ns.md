# Function: <code>ktime_get_mono_fast_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850096,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:410",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_ktime_get_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850096,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874368,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:413",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_ktime_get_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874368,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886080,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:413",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886080,
      "name": "ktime_get_mono_fast_ns",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579895136,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:439",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895136,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944752,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:458",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944752,
      "name": "ktime_get_mono_fast_ns",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992736,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:459",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992736,
      "name": "ktime_get_mono_fast_ns",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039360,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:466",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_set_runtime_active",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:pm_runtime_autosuspend_expiration",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039360,
      "name": "ktime_get_mono_fast_ns",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082336,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:472",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_set_runtime_active",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082336,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131408,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:472",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131408,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580190736,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:472",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_might_be_idle",
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190736,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580175488,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:485",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_might_be_idle",
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580175488,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580179312,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:485",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:spi_set_cs_timing",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580179312,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:485",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592152106,
      "name": "ktime_get_mono_fast_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071580325392,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:490",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_tai_fast_ns",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_post_runtime_resume",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/base/power/domain.c:total_idle_time_show",
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/power/domain.c:genpd_update_accounting",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593927106,
      "name": "ktime_get_mono_fast_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071580537504,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:490",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_tai_fast_ns",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_post_runtime_resume",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/base/power/domain.c:total_idle_time_show",
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/power/domain.c:genpd_update_accounting",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595995083,
      "name": "ktime_get_mono_fast_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071580793856,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:490",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_tai_fast_ns",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_post_runtime_resume",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/tty/serial/serial_port.c:serial_port_runtime_resume",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/base/power/domain.c:total_idle_time_show",
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/base/power/domain.c:genpd_update_accounting",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596513475,
      "name": "ktime_get_mono_fast_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071580877392,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:490",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_tai_fast_ns",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pmdomain/core.c:total_idle_time_show",
        "drivers/pmdomain/core.c:active_time_show",
        "drivers/pmdomain/core.c:idle_states_show",
        "drivers/pmdomain/core.c:pm_genpd_init",
        "drivers/pmdomain/core.c:genpd_update_accounting",
        "drivers/tty/serial/serial_core.c:__uart_start",
        "drivers/tty/serial/serial_port.c:serial_port_runtime_suspend",
        "drivers/tty/serial/serial_port.c:serial_port_runtime_resume",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_force_suspend",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597412802,
      "name": "ktime_get_mono_fast_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071580967824,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491351832,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:472",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_close",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_master_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491351832,
      "name": "ktime_get_mono_fast_ns",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225345172,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:472",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/tty/serial/omap-serial.c:serial_omap_config_rs485",
        "drivers/tty/serial/omap-serial.c:serial_omap_console_write",
        "drivers/tty/serial/omap-serial.c:serial_omap_poll_get_char",
        "drivers/tty/serial/omap-serial.c:serial_omap_poll_put_char",
        "drivers/tty/serial/omap-serial.c:serial_omap_pm",
        "drivers/tty/serial/omap-serial.c:serial_omap_set_termios",
        "drivers/tty/serial/omap-serial.c:serial_omap_shutdown",
        "drivers/tty/serial/omap-serial.c:serial_omap_break_ctl",
        "drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl",
        "drivers/tty/serial/omap-serial.c:serial_omap_get_mctrl",
        "drivers/tty/serial/omap-serial.c:serial_omap_tx_empty",
        "drivers/tty/serial/omap-serial.c:serial_omap_irq",
        "drivers/tty/serial/omap-serial.c:serial_omap_unthrottle",
        "drivers/tty/serial/omap-serial.c:serial_omap_throttle",
        "drivers/tty/serial/omap-serial.c:serial_omap_start_tx",
        "drivers/tty/serial/omap-serial.c:serial_omap_stop_rx",
        "drivers/tty/serial/omap-serial.c:serial_omap_stop_tx",
        "drivers/tty/serial/omap-serial.c:serial_omap_enable_ms",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_close",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_autosuspend_device",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/musb/musb_core.c:musb_resume",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_stop",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_start",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_work",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_queue",
        "drivers/usb/musb/musb_debugfs.c:musb_softconnect_write",
        "drivers/usb/musb/musb_debugfs.c:musb_softconnect_show",
        "drivers/usb/musb/musb_debugfs.c:musb_test_mode_write",
        "drivers/usb/musb/musb_debugfs.c:musb_test_mode_show",
        "drivers/usb/musb/musb_debugfs.c:musb_regdump_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:mmc_regs_show",
        "sound/soc/soc-pcm.c:soc_pcm_close",
        "sound/soc/soc-pcm.c:soc_pcm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225345172,
      "name": "ktime_get_mono_fast_ns",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284285040,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:472",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284285040,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271846126,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:472",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271846126,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580100608,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:472",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100608,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580045920,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:472",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045920,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580091680,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:472",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091680,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
u64 ktime_get_mono_fast_ns()
```

```json
{
  "name": "ktime_get_mono_fast_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580143424,
      "name": "ktime_get_mono_fast_ns",
      "external": true,
      "loc": "kernel/time/timekeeping.c:472",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/time/timekeeping.c:ktime_get_boot_fast_ns",
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "kernel/bpf/helpers.c:bpf_ktime_get_ns",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/base/power/runtime.c:pm_runtime_force_resume",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/mfd/arizona-core.c:arizona_wait_for_boot",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_suspend",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_resume_both",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143424,
      "name": "ktime_get_mono_fast_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
