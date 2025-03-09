# Function: <code>ktime_divns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "arch/x86/events/intel/rapl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579823167,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871946,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579886622,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_do_update_jiffies64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584431215,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "drivers/power/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585902464,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585905137,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579706594,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579713099,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851902,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579901242,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579915905,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats",
        "kernel/time/tick-sched.c:tick_do_update_jiffies64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584767087,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584800650,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:print_wakeup_source_stats",
        "drivers/base/power/wakeup.c:print_wakeup_source_stats",
        "drivers/base/power/wakeup.c:print_wakeup_source_stats",
        "drivers/base/power/wakeup.c:print_wakeup_source_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586068178,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "drivers/power/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/charger-manager.c:cm_suspend_complete",
        "drivers/power/charger-manager.c:try_charger_enable",
        "drivers/power/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586304714,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586310439,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587338823,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:188",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579734162,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579740635,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880752,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579911402,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579946433,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584240515,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584957487,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584992650,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:print_wakeup_source_stats",
        "drivers/base/power/wakeup.c:print_wakeup_source_stats",
        "drivers/base/power/wakeup.c:print_wakeup_source_stats",
        "drivers/base/power/wakeup.c:print_wakeup_source_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586265922,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586512554,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586518151,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587541767,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579102853,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579730067,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579736763,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579889625,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579919920,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579954329,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584316544,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585042335,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585077044,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:print_wakeup_source_stats",
        "drivers/base/power/wakeup.c:print_wakeup_source_stats",
        "drivers/base/power/wakeup.c:print_wakeup_source_stats",
        "drivers/base/power/wakeup.c:print_wakeup_source_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586361601,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586638180,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586643818,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587687820,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579115314,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579763076,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579769947,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579934143,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579965136,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579999984,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584715991,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585465007,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585500449,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:print_wakeup_source_stats",
        "drivers/base/power/wakeup.c:print_wakeup_source_stats",
        "drivers/base/power/wakeup.c:print_wakeup_source_stats",
        "drivers/base/power/wakeup.c:print_wakeup_source_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585509522,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_active_time_show",
        "drivers/base/power/domain.c:genpd_idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586826401,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587119531,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587125389,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588214556,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579797579,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579806713,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579980643,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580012736,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580052114,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584943444,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585709663,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585745025,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585754235,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_active_time_show",
        "drivers/base/power/domain.c:genpd_idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587118424,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587143749,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587419190,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587426373,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588569224,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:162",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579844187,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579853353,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580027299,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580059648,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580098930,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585047428,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585803881,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585840527,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585877777,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585887755,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587296904,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587324421,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587599405,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587607268,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766248,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579876940,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579878907,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579887586,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580071731,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580103356,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580143530,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584319360,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585251668,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586038715,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586077119,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586116961,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586129359,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587568917,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587595317,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587876705,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587884146,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587885532,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589199276,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579923404,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579929115,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579937838,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580119593,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580152224,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580190810,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584161765,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584453984,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585389476,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586184251,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586225295,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586262452,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586266578,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586273727,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587770181,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587798757,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588081813,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588089938,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588091022,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589424540,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579967180,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579973149,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579981837,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580180348,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580217892,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580257811,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584559009,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585017392,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586099044,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586945918,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586991343,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587031588,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587035314,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show",
        "drivers/base/power/wakeup_stats.c:active_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587040134,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:total_idle_time_show",
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588616519,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:check_charging_duration",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588645087,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588943114,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588947397,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/cpuidle/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/sysfs.c:show_state_time",
        "drivers/cpuidle/sysfs.c:show_state_target_residency",
        "drivers/cpuidle/sysfs.c:show_state_exit_latency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588950504,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_update"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579955100,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591291216,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591293094,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580165276,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580202740,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580241395,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584676116,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585165928,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586219716,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587030622,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587075987,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587115236,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587118706,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show",
        "drivers/base/power/wakeup_stats.c:active_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587123362,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:total_idle_time_show",
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588638424,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:check_charging_duration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588667263,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588955502,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588959653,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/sysfs.c:show_state_time",
        "drivers/cpuidle/sysfs.c:show_state_target_residency",
        "drivers/cpuidle/sysfs.c:show_state_exit_latency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588962760,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_update"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579957820,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591234249,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591236089,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580169852,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580208036,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580245715,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584704663,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585046456,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586094276,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586362458,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586914405,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586962259,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587001508,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587005106,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show",
        "drivers/base/power/wakeup_stats.c:active_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587009635,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:total_idle_time_show",
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588523528,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:check_charging_duration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588549935,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588844451,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588848149,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/sysfs.c:show_state_time",
        "drivers/cpuidle/sysfs.c:show_state_target_residency",
        "drivers/cpuidle/sysfs.c:show_state_exit_latency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588852333,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580087180,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592122327,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592123746,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314716,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580353732,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580396399,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585128109,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585489816,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586592101,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586886477,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587476138,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587528403,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587552433,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587567748,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587571634,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show",
        "drivers/base/power/wakeup_stats.c:active_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587576195,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:total_idle_time_show",
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589197298,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:check_charging_duration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589223871,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589541699,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589546869,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/sysfs.c:show_state_time",
        "drivers/cpuidle/sysfs.c:show_state_target_residency",
        "drivers/cpuidle/sysfs.c:show_state_exit_latency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589552057,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578848427,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580223964,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580229895,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593893232,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580525564,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580568144,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580616003,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585850785,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586634450,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587853511,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588175861,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588796468,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588858575,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588885777,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588902340,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588906738,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show",
        "drivers/base/power/wakeup_stats.c:active_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589904317,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed",
        "drivers/cdrom/cdrom.c:cdrom_select_disc",
        "drivers/cdrom/cdrom.c:cdrom_select_disc",
        "drivers/cdrom/cdrom.c:register_cdrom"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590657558,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:check_charging_duration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590687391,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591031443,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591040117,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/sysfs.c:show_state_time",
        "drivers/cpuidle/sysfs.c:show_state_target_residency",
        "drivers/cpuidle/sysfs.c:show_state_exit_latency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591045586,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578849483,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580414988,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580421902,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580431419,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781340,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580828624,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880947,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586623646,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587877650,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589196335,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589587335,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590292694,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590364895,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590395603,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590413764,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590418466,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show",
        "drivers/base/power/wakeup_stats.c:active_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591481149,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed",
        "drivers/cdrom/cdrom.c:cdrom_select_disc",
        "drivers/cdrom/cdrom.c:cdrom_select_disc",
        "drivers/cdrom/cdrom.c:register_cdrom"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592323542,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:check_charging_duration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592357105,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592742019,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592751669,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/sysfs.c:show_state_time",
        "drivers/cpuidle/sysfs.c:show_state_target_residency",
        "drivers/cpuidle/sysfs.c:show_state_exit_latency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592757538,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578848907,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580483868,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580491267,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580500651,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864332,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912176,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580962713,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586893206,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588149443,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589490495,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589889050,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590612926,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590685391,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590718006,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590733300,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590737969,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show",
        "drivers/base/power/wakeup_stats.c:active_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591905899,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed",
        "drivers/cdrom/cdrom.c:cdrom_select_disc",
        "drivers/cdrom/cdrom.c:cdrom_select_disc",
        "drivers/cdrom/cdrom.c:register_cdrom"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592750230,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:check_charging_duration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592783745,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596941744,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593186389,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/sysfs.c:show_state_time",
        "drivers/cpuidle/sysfs.c:show_state_target_residency",
        "drivers/cpuidle/sysfs.c:show_state_exit_latency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593192847,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:148",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578848923,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:trace_initcall_finish_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580543708,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551155,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580560539,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954796,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581002704,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_forward",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581054569,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587171221,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588439043,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589797711,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590226698,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590972030,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591046847,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591080166,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591095268,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591099937,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show",
        "drivers/base/power/wakeup_stats.c:active_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592229640,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/gpu/drm/drm_atomic_helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_atomic_helper.c:commit_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592645738,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed",
        "drivers/cdrom/cdrom.c:cdrom_select_disc",
        "drivers/cdrom/cdrom.c:cdrom_select_disc",
        "drivers/cdrom/cdrom.c:register_cdrom"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593498182,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:check_charging_duration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593532577,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597869216,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593940213,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/cpuidle/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/sysfs.c:show_state_time",
        "drivers/cpuidle/sysfs.c:show_state_target_residency",
        "drivers/cpuidle/sysfs.c:show_state_exit_latency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593946873,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594861102,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:146",
      "file": "net/core/page_pool_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool_user.c:page_pool_detached"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491131700,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491137876,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491337544,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491371536,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491420272,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496010940,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496340056,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497662596,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498982516,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499035468,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499084936,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499091320,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499096252,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500923240,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/media/cec/cec-pin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500968036,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501000512,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501325296,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501336824,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501337892,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503078684,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
s64 ktime_divns(const ktime_t kt, s64 div)
```

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225029156,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:start_dl_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 3225133268,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 3225134336,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ]
    },
    {
      "addr": 3225142748,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 3225335832,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ]
    },
    {
      "addr": 3225371988,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ]
    },
    {
      "addr": 3225415916,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us"
      ],
      "caller_func": []
    },
    {
      "addr": 3229356712,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    },
    {
      "addr": 3229673476,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 3230705868,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/clk/samsung/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230762480,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/clk/ti/clkctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231548340,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:driver_probe_device"
      ]
    },
    {
      "addr": 3231595760,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231639212,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show"
      ]
    },
    {
      "addr": 3231643032,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show",
        "drivers/base/power/wakeup_stats.c:active_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3231661600,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": [
        "drivers/base/power/domain.c:total_idle_time_show"
      ]
    },
    {
      "addr": 3232814336,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233409200,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/i2c/busses/i2c-s3c2410.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 3233478812,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ]
    },
    {
      "addr": 3233513104,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3233814324,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    },
    {
      "addr": 3233824308,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ]
    },
    {
      "addr": 3233826644,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    },
    {
      "addr": 3234078520,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "drivers/firmware/tegra/bpmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic"
      ],
      "caller_func": [
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe"
      ]
    },
    {
      "addr": 3235760448,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:147",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225134336,
      "name": "ktime_divns.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 3225335832,
      "name": "ktime_divns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 3225371988,
      "name": "ktime_divns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 3225413900,
      "name": "ktime_divns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 3229351248,
      "name": "ktime_divns.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 3231548340,
      "name": "ktime_divns.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3231595760,
      "name": "ktime_divns.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 3231639212,
      "name": "ktime_divns.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 3231654200,
      "name": "ktime_divns.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 3233478812,
      "name": "ktime_divns.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 3233814324,
      "name": "ktime_divns.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3233824308,
      "name": "ktime_divns.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3233826644,
      "name": "ktime_divns.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3234078108,
      "name": "ktime_divns.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283118208,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "arch/powerpc/platforms/pseries/lpar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt",
        "arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284022380,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284030348,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284269232,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284311008,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284366916,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290244652,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290664192,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292134004,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292205116,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292265016,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292272748,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292280500,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294432632,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294475984,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294869328,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294883540,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294884828,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296782656,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271703004,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271835088,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271862394,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271887792,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275105808,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275390052,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276360180,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276423062,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277726310,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277751240,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279133376,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579895516,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900763,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905678,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580088793,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580121424,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580159610,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584130501,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584422720,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585174996,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585944619,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585985503,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586025780,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586029826,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586036975,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586478633,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_init_identify"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587429733,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587703637,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587711531,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587712606,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589028908,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579830476,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579836187,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579844846,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580034121,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580066720,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580105754,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584066133,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584357920,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585116692,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585793707,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585834767,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585871732,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585875842,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585882991,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586354809,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_init_identify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587197941,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587481898,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587490018,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587491102,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588753948,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579883676,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579889387,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579898110,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580079865,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580112496,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580151082,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584114261,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584405632,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585339876,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586134267,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586175311,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586212468,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586216594,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586223743,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587726325,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587754901,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588037957,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588046082,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589465772,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ktime_divns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579929436,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579935211,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944142,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580131369,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580164256,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580203162,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us",
        "kernel/time/tick-sched.c:update_ts_time_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584217413,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584511696,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585447188,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586242859,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586284657,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586321540,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586325698,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586333167,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587809302,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/media/cec/cec-pin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587839381,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/power/supply/charger-manager.c:try_charger_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587867397,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588153541,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588161890,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588162974,
      "name": "ktime_divns",
      "external": false,
      "loc": "include/linux/ktime.h:165",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
s64 ktime_divns(const ktime_t kt, s64 div)
```
</details>
</li>
</ul>
