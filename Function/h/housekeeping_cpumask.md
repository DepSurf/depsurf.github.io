# Function: <code>housekeeping_cpumask</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579746224,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:30",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746224,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579780592,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:25",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780592,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579823472,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:25",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823472,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851680,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:32",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851680,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579900176,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900176,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579943328,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:hk_should_isolate",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943328,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579931584,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:hk_should_isolate",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/base/cpu.c:print_cpus_isolated",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931584,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939424,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/base/cpu.c:print_cpus_isolated",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939424,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580064448,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:asym_cpu_capacity_scan",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/base/cpu.c:print_cpus_isolated",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064448,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct cpumask * housekeeping_cpumask(enum hk_type type)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580201861,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:56",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:kthread",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/base/cpu.c:print_cpus_isolated",
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593879848,
      "name": "housekeeping_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580140656,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct cpumask * housekeeping_cpumask(enum hk_type type)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580392870,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:56",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:kthread",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/base/cpu.c:print_cpus_isolated",
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595981640,
      "name": "housekeeping_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580315776,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct cpumask * housekeeping_cpumask(enum hk_type type)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580461250,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:56",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:kthread",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/base/cpu.c:print_cpus_isolated",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596499822,
      "name": "housekeeping_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580382544,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct cpumask * housekeeping_cpumask(enum hk_type type)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580520920,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:56",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan"
      ],
      "caller_func": [
        "kernel/cpu.c:cpu_down_maps_locked",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:kthread",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/cgroup/cpuset.c:prstate_housekeeping_conflict",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/base/cpu.c:print_cpus_isolated",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597397302,
      "name": "housekeeping_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580439280,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491099336,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491099336,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225102628,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225102628,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283989488,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283989488,
      "name": "housekeeping_cpumask",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271681450,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271681450,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872288,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872288,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579807296,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807296,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579860448,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860448,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579905824,
      "name": "housekeeping_cpumask",
      "external": true,
      "loc": "kernel/sched/isolation.c:40",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:lockup_detector_init",
        "drivers/base/cpu.c:print_cpus_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905824,
      "name": "housekeeping_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
const struct cpumask * housekeeping_cpumask(enum hk_flags flags)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum hk_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>enum hk_flags flags</code>
</li>
</ul>
</details>
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
