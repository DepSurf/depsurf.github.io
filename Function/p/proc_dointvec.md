# Function: <code>proc_dointvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579405408,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2190",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/sched/core.c:sched_rr_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "fs/quota/dquot.c:do_proc_dqstats",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405408,
      "name": "proc_dointvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579416217,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2317",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:moksbstate_disabled_proc_handler",
        "kernel/sysctl.c:secure_boot_proc_handler"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_handler",
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "fs/quota/dquot.c:do_proc_dqstats",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416064,
      "name": "proc_dointvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579436521,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2302",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:moksbstate_disabled_proc_handler",
        "kernel/sysctl.c:secure_boot_proc_handler"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_handler",
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "fs/quota/dquot.c:do_proc_dqstats",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436368,
      "name": "proc_dointvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579426192,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2459",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "fs/quota/dquot.c:do_proc_dqstats",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426192,
      "name": "proc_dointvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579453200,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2449",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "fs/quota/dquot.c:do_proc_dqstats",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453200,
      "name": "proc_dointvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579467744,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2454",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "fs/quota/dquot.c:do_proc_dqstats",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467744,
      "name": "proc_dointvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501296,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2502",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "fs/quota/dquot.c:do_proc_dqstats",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501296,
      "name": "proc_dointvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579519536,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2588",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "fs/quota/dquot.c:do_proc_dqstats",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519536,
      "name": "proc_dointvec",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579545616,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2590",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545616,
      "name": "proc_dointvec",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579579552,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:802",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579552,
      "name": "proc_dointvec",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561168,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:801",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561168,
      "name": "proc_dointvec",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565248,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:813",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565248,
      "name": "proc_dointvec",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579635232,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:857",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635232,
      "name": "proc_dointvec",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579731168,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:737",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/build_policy.c:sched_rr_handler",
        "kernel/sched/build_policy.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "net/core/sysctl_net_core.c:proc_do_dev_weight",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731168,
      "name": "proc_dointvec",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579867063,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:744",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_dobool"
      ],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/build_policy.c:sched_rr_handler",
        "kernel/sched/build_policy.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "net/core/sysctl_net_core.c:proc_do_dev_weight",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/sysctl_net_ipv4.c:proc_udp_hash_entries",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_ehash_entries",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866016,
      "name": "proc_dointvec",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917143,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:743",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_dobool"
      ],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/build_policy.c:sched_rr_handler",
        "kernel/sched/build_policy.c:sched_rt_handler",
        "kernel/kexec_core.c:kexec_limit_handler",
        "kernel/kexec_core.c:kexec_limit_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "net/core/sysctl_net_core.c:proc_do_dev_weight",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/sysctl_net_ipv4.c:proc_udp_hash_entries",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_ehash_entries",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916096,
      "name": "proc_dointvec",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579956391,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:743",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_dobool"
      ],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/build_policy.c:sched_rr_handler",
        "kernel/kexec_core.c:kexec_limit_handler",
        "kernel/kexec_core.c:kexec_limit_handler",
        "kernel/latencytop.c:sysctl_latencytop",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "security/apparmor/lsm.c:userns_restrict_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "net/core/sysctl_net_core.c:proc_do_dev_weight",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/sysctl_net_ipv4.c:proc_udp_hash_entries",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_ehash_entries",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955344,
      "name": "proc_dointvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490694032,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2590",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/fpsimd.c:sve_proc_do_default_vl",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490694032,
      "name": "proc_dointvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224761896,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2590",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224761896,
      "name": "proc_dointvec",
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
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283520480,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2590",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283520480,
      "name": "proc_dointvec",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271426344,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2590",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271426344,
      "name": "proc_dointvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579519280,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2590",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519280,
      "name": "proc_dointvec",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579448080,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2590",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448080,
      "name": "proc_dointvec",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579519200,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2590",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519200,
      "name": "proc_dointvec",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579552160,
      "name": "proc_dointvec",
      "external": true,
      "loc": "kernel/sysctl.c:2590",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/rt.c:sched_rr_handler",
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/latencytop.c:sysctl_latencytop",
        "kernel/trace/ftrace.c:ftrace_enable_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace_stack.c:stack_trace_sysctl",
        "mm/page-writeback.c:dirty_writeback_centisecs_handler",
        "mm/util.c:overcommit_ratio_handler",
        "ipc/ipc_sysctl.c:proc_ipc_sem_dointvec",
        "ipc/mq_sysctl.c:proc_mq_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "drivers/char/random.c:proc_do_entropy",
        "net/core/sysctl_net_core.c:flow_limit_table_len_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/neighbour.c:neigh_proc_dointvec",
        "net/ipv4/devinet.c:ipv4_doint_and_flush",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/route.c:ipv6_sysctl_rtcache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552160,
      "name": "proc_dointvec",
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
