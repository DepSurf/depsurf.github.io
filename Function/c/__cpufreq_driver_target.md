# Function: <code>__cpufreq_driver_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585854352,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1843",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_governor_userspace",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_governor_userspace",
        "drivers/cpufreq/cpufreq_ondemand.c:dbs_freq_increase",
        "drivers/cpufreq/cpufreq_ondemand.c:od_check_cpu",
        "drivers/cpufreq/cpufreq_ondemand.c:od_check_cpu",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer",
        "drivers/cpufreq/cpufreq_conservative.c:cs_check_cpu",
        "drivers/cpufreq/cpufreq_conservative.c:cs_check_cpu",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585854352,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586256624,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1941",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_timer",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_timer",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586256624,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1610
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586463472,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1913",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586463472,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1463
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586587744,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1916",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586587744,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1373
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587071056,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1949",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587071056,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1391
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1948",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587377576,
      "name": "__cpufreq_driver_target.cold.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071587369360,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1949",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587557480,
      "name": "__cpufreq_driver_target.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071587548928,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1458
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2099",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587832990,
      "name": "__cpufreq_driver_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071587823968,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2113",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588037964,
      "name": "__cpufreq_driver_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071588029280,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1421
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588891968,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2150",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588891968,
      "name": "__cpufreq_driver_target",
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588903968,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2226",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588903968,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 845
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588792480,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2232",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588792480,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589485520,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2238",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589485520,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2270",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_limits",
        "kernel/sched/build_utility.c:sugov_limits",
        "kernel/sched/build_utility.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594541610,
      "name": "__cpufreq_driver_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590966192,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2267",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_limits",
        "kernel/sched/build_utility.c:sugov_limits",
        "kernel/sched/build_utility.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596313968,
      "name": "__cpufreq_driver_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071592669648,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2274",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_limits",
        "kernel/sched/build_utility.c:sugov_limits",
        "kernel/sched/build_utility.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596842889,
      "name": "__cpufreq_driver_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593100400,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2315",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_limits",
        "kernel/sched/build_utility.c:sugov_limits",
        "kernel/sched/build_utility.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597768035,
      "name": "__cpufreq_driver_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593853168,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501292360,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2113",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501292360,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1644
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233780520,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2113",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233780520,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1564
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
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294818784,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2113",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294818784,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1968
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2113",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587662956,
      "name": "__cpufreq_driver_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071587654272,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2113",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436828,
      "name": "__cpufreq_driver_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071587428144,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2113",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587994108,
      "name": "__cpufreq_driver_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071587985424,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "__cpufreq_driver_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpufreq_driver_target",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2113",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_limits",
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq_performance.c:cpufreq_gov_performance_limits",
        "drivers/cpufreq/cpufreq_powersave.c:cpufreq_gov_powersave_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_limits",
        "drivers/cpufreq/cpufreq_userspace.c:cpufreq_set",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588109455,
      "name": "__cpufreq_driver_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071588097552,
      "name": "__cpufreq_driver_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1421
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __cpufreq_driver_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```
</details>
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
