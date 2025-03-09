# Function: <code>lockdep_assert_cpus_held</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579396432,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:238",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/padata.c:padata_alloc_possible"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396432,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579424512,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:313",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/padata.c:padata_alloc_possible"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424512,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579439760,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:310",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/padata.c:padata_alloc_possible"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439760,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579471664,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:314",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/jump_label.c:static_key_disable_cpuslocked",
        "kernel/jump_label.c:static_key_enable_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471664,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579489456,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:315",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/jump_label.c:static_key_disable_cpuslocked",
        "kernel/jump_label.c:static_key_enable_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489456,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579515392,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:318",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515392,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579544272,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:319",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_root_domains",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:do_unoptimize_kprobes",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout",
        "kernel/jump_label.c:static_key_disable_cpuslocked",
        "kernel/jump_label.c:static_key_enable_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544272,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579525984,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:319",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_root_domains",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:do_unoptimize_kprobes",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout",
        "kernel/jump_label.c:static_key_disable_cpuslocked",
        "kernel/jump_label.c:static_key_enable_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525984,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579529920,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:324",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout",
        "kernel/jump_label.c:static_key_disable_cpuslocked",
        "kernel/jump_label.c:static_key_enable_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529920,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579602096,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:335",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout",
        "kernel/jump_label.c:static_key_disable_cpuslocked",
        "kernel/jump_label.c:static_key_enable_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked",
        "mm/slub.c:flush_all_cpus_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602096,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579694576,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:336",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout",
        "kernel/jump_label.c:static_key_disable_cpuslocked",
        "kernel/jump_label.c:static_key_enable_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked",
        "mm/slub.c:flush_all_cpus_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694576,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579818448,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:336",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout",
        "kernel/jump_label.c:static_key_disable_cpuslocked",
        "kernel/jump_label.c:static_key_enable_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked",
        "mm/slub.c:flush_all_cpus_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818448,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579867776,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:515",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_perf.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_perf.c:hardlockup_detector_perf_stop",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout",
        "kernel/jump_label.c:static_key_disable_cpuslocked",
        "kernel/jump_label.c:static_key_enable_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked",
        "mm/slub.c:flush_all_cpus_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867776,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579905680,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:515",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_unbound_exclude_cpumask",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:remote_cpus_update",
        "kernel/cgroup/cpuset.c:remote_cpus_update",
        "kernel/cgroup/cpuset.c:remote_partition_disable",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_perf.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_perf.c:hardlockup_detector_perf_stop",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout",
        "kernel/jump_label.c:static_key_disable_cpuslocked",
        "kernel/jump_label.c:static_key_enable_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked",
        "mm/slub.c:flush_all_cpus_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905680,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490652424,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:318",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/jump_label.c:static_key_disable_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490652424,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224729112,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:318",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224729112,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283474608,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:318",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_rebuild",
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_teardown",
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/jump_label.c:static_key_enable_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283474608,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "lockdep_assert_cpus_held",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "lockdep_assert_cpus_held",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "lockdep_assert_cpus_held",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "lockdep_assert_cpus_held",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/stop_machine.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579489056,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:318",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489056,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579417920,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:318",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417920,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579488976,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:318",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488976,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void lockdep_assert_cpus_held()
```

```json
{
  "name": "lockdep_assert_cpus_held",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579521360,
      "name": "lockdep_assert_cpus_held",
      "external": true,
      "loc": "kernel/cpu.c:318",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:apply_workqueue_attrs",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/kprobes.c:force_unoptimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521360,
      "name": "lockdep_assert_cpus_held",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void lockdep_assert_cpus_held()
```
</details>
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
void lockdep_assert_cpus_held()
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
